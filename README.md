## Shoukat Abbas — SK Malik

**Data migration and workflow automation.** Mianwali, Pakistan · UTC+5

I move data between systems and build the small tools that make the move stick — Google Workspace, Apps Script, CSV and contact exports, n8n / Make / Zapier workflows, and the APIs behind them.

The work I get asked for most is the unglamorous kind: an export where the same person appears three times under three spellings, a Drive tree that has to survive a migration exactly as it was, a workflow that stopped firing last Tuesday and nobody knows why. My approach to all three is the same — inventory and verify before anything moves, and never let a system guess when it should stop and ask.

---

### Projects here

**[table-to-sheets](https://github.com/skmalikllc/table-to-sheets)** — Chrome extension (MV3)
Pulls any HTML table off a page as CSV, or as a clipboard payload that pastes cleanly into Google Sheets. The part that usually breaks is merged cells: a `rowspan` silently shifts every following row one column left, so the sheet looks right until someone sorts it. This expands `rowspan`/`colspan` into a proper rectangle first. RFC 4180 quoting, UTF-8 BOM so Excel opens accented text. Extraction logic is pure JS with no browser APIs, covered by 7 unit tests over jsdom.

**[contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp)** — MCP server
Four tools over stdio that let Claude work on a contact export: profile it, find the rows that are the same person, merge them, and report every conflict instead of quietly dropping it. Gmail dot and plus-tag rules on email, last-9-digits on phone, order-insensitive name comparison. A shared email or phone is strong evidence; a similar name on its own is not. 9 unit tests plus an end-to-end run that speaks the real protocol.

Both are my own tools, written to solve problems that keep coming up in client work, then cleaned up so the code can be read.

---

### What I work with

`Google Apps Script` · `Google Workspace` · `Google Sheets API` · `Node.js` · `JavaScript` · `Python` · `MCP` · `Chrome Extensions (MV3)` · `n8n` · `Make.com` · `Zapier` · `REST APIs & webhooks` · `CSV / data cleaning` · `Supabase` · `WordPress / WooCommerce`

---

### Background

Around twenty years of technical, administrative, operations and training work — first in Pakistan Air Force service, then remote and freelance. That is where the habit of writing things down before touching them comes from.

On Upwork: **100% Job Success**, Rising Talent, five completed contracts, every one rated 5.0. The reviewed work is Google Workspace and automation — an n8n build, iCloud-to-Google contact sync, Google Contacts backup automation, a Mega-to-Drive folder transfer with the structure kept intact, and Sheets script fixes.

> "He did an outstanding job on our n8n automation project. They quickly understood our workflow requirements, provided expert insights, and delivered a clean, efficient solution ahead of schedule." — Upwork client, Nov 2025

---

### Get in touch

- Upwork — [upwork.com/freelancers/skmalik1](https://www.upwork.com/freelancers/skmalik1)

Open to short migrations and cleanups, small builds, and ongoing automation support.
