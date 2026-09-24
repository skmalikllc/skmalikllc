# SK Malik — Automation, Integrations & Data Migration

**n8n · Make · Google Workspace · Apps Script · APIs · Webhooks · Data Sync**

Mianwali, Pakistan · UTC+5 · available for remote work

---

I build the automations and data plumbing that small businesses and agencies
run on, and I move data between systems without losing it on the way.

**What I do for clients**

- **Workflow automation** — n8n, Make and Zapier-style builds: the scheduled
  job, the form that has to reach three places, the alert nobody wants to send
  by hand.
- **Google Workspace automation** — Apps Script for Sheets, Gmail, Drive,
  Forms and Calendar; the small internal tools a team actually uses.
- **API and webhook integration** — connecting apps that have no native
  integration, including authentication, retries and error handling.
- **Data migration** — Drive, OneDrive, Dropbox, Mega and CRM exports moved
  with the folder structure and the sharing intact.
- **Data sync and cleanup** — contact and CRM exports deduplicated, normalised
  and kept in step between two systems.
- **MCP servers** — tools that let Claude work directly on a client's files and
  data instead of describing what to do.

Most of what I get asked for is the unglamorous kind of work: an export where
the same person appears three times under three spellings, a Drive tree that
has to survive a migration exactly as it was, a workflow that stopped firing
last Tuesday and nobody knows why. My approach to all three is the same —
inventory and verify before anything moves, and never let an automation guess
when it should stop and ask.

---

## Proof

| Where | Record |
|---|---|
| **Upwork** | 100% Job Success · Rising Talent · 5 completed contracts, every one rated **5.0** |
| **Fiverr** | **4.9 ★ from 109 reviews** · Level 1 seller |
| **Here** | 2 tools of my own, both with tests running in CI on every push |

The reviewed Upwork work is Google Workspace and automation: an n8n build,
iCloud-to-Google contact sync, a Google Contacts backup automation, a
Mega-to-Drive folder transfer with the structure kept intact, and Google Sheets
script fixes.

> "He did an outstanding job on our n8n automation project. They quickly
> understood our workflow requirements, provided expert insights, and delivered
> a clean, efficient solution ahead of schedule."
> — Upwork client, November 2025

---

## Open-source tools

**[table-to-sheets](https://github.com/skmalikllc/table-to-sheets)** — Chrome
extension (MV3) &nbsp;·&nbsp; ![tests](https://github.com/skmalikllc/table-to-sheets/actions/workflows/tests.yml/badge.svg)

Pulls any HTML table off a page as CSV, or as a clipboard payload that pastes
cleanly into Google Sheets. The part that usually breaks is merged cells: a
`rowspan` silently shifts every following row one column left, so the sheet
looks right until someone sorts it. This expands `rowspan`/`colspan` into a
rectangle first. RFC 4180 quoting, UTF-8 BOM so Excel opens accented text.
7 unit tests over jsdom.

**[contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp)** — MCP
server &nbsp;·&nbsp; ![tests](https://github.com/skmalikllc/contact-dedupe-mcp/actions/workflows/tests.yml/badge.svg)

Four tools over stdio that let Claude work on a contact export: profile it, find
the rows that are the same person, merge them, and report every conflict
instead of quietly dropping it. Gmail dot and plus-tag rules on email,
last-9-digits on phone, order-insensitive name comparison. 9 unit tests plus an
end-to-end run that speaks the real protocol.

Both are my own tools, written to solve problems that keep coming up in client
work, then cleaned up so the code can be read.

---

## Client case studies

Sanitized write-ups of completed, reviewed client work — no client names, data,
credentials or documents.

**[gmail-business-inbox-organization](https://github.com/skmalikllc/gmail-business-inbox-organization)**
Four completed engagements reorganising overloaded business Gmail accounts:
labels, filters and folders built around how the business actually works, so
the inbox stops refilling. All rated 5 stars; two became ongoing relationships.

**[google-drive-file-organization](https://github.com/skmalikllc/google-drive-file-organization)**
Drive structure work and cloud-to-cloud migrations across Upwork and Fiverr,
2023–2025 — including a Mega → Google Drive transfer with the folder structure
kept intact.

Everything is indexed in
**[automation-portfolio](https://github.com/skmalikllc/automation-portfolio)**.

---

## What I work with

**Automation** — n8n · Make.com · Zapier · Google Apps Script · scheduled jobs and triggers

**Google Workspace** — Sheets · Gmail · Drive · Forms · Calendar · Contacts · Sheets API · Drive API

**Integration** — REST APIs · webhooks · OAuth · JSON · MCP (Model Context Protocol) · Supabase

**Data** — CSV and data cleaning · deduplication · contact and CRM exports · Drive / OneDrive / Dropbox / Mega migrations · data sync

**Development** — JavaScript · Node.js · Python · Chrome Extensions (MV3) · HTML / CSS · Git

**Other platforms** — WordPress / WooCommerce · Shopify · Jotform · OpenAI and Claude API integrations

---

## Background

Around twenty years of technical, administrative, operations and training work —
first in Pakistan Air Force service, then remote and freelance. That is where the
habit of writing everything down before touching it comes from.

---

## Get in touch

- **Upwork** — [upwork.com/freelancers/skmalik1](https://www.upwork.com/freelancers/skmalik1)
- **Fiverr** — [fiverr.com/skmalik166](https://www.fiverr.com/skmalik166)

Open to short migrations and cleanups, small builds, and ongoing automation
support.
