<img src="https://raw.githubusercontent.com/skmalikllc/automation-portfolio/main/assets/hero.png" alt="SK Malik — Automation, Integrations & Business Systems" width="100%">

# SK Malik — Automation, Integrations & Business Systems

I build the automations, integrations and data plumbing that small businesses and
agencies run on, and I move data between systems without losing it on the way.
Most of what I am handed is the unglamorous kind of work: an export where the same
person appears three times under three spellings, a file estate that has to survive
a migration exactly as it was, a workflow that stopped firing last Tuesday and
nobody knows why.

**200+ completed freelance engagements · 10+ years of client work · Google Workspace · Workflow automation · Mianwali, Pakistan (UTC+5)**

---

## What I build

**⚙️ Workflow Automation** — `n8n` `Make` `Zapier`
Multi-app workflows, scheduled processing, operational automation and the
integrations between tools that have no native connection.

**📄 Google Workspace Systems** — `Apps Script` `Sheets` `Gmail` `Drive` `Contacts` `Forms`
Internal tools a team actually uses: scripted spreadsheets, generated forms,
mailbox structure, and the Workspace troubleshooting nobody else wants.

**🔌 API & Data Integration** — `REST APIs` `Webhooks` `JSON` `Data mapping`
Connecting two systems that were never designed to talk to each other, including
the authentication and the failure behaviour.

**🧹 Data Sync & Quality** — `Deduplication` `Reconciliation` `Cleanup`
Contact and CRM exports matched, merged and kept in step — with every conflicting
value reported rather than quietly dropped.

**☁️ Cloud Migration** — `Google Drive` `OneDrive` `Dropbox` `Mega`
File estates moved between providers with the folder structure and names intact,
and verified afterwards rather than assumed.

**🗂️ Client Operations Systems** — `Jotform` `Intake` `CRM workflows` `File architecture`
The form work arrives through, where it goes next, and the structure that keeps it
findable six months later.

---

## Selected work

The strongest eight. The full index — **19 repositories, organised by discipline** — is
in **[automation-portfolio](https://github.com/skmalikllc/automation-portfolio)**.

| Project | What it is | Type |
|---|---|---|
| **[automation-portfolio](https://github.com/skmalikllc/automation-portfolio)** | The full portfolio index, organised by discipline, with proof for each system | Index |
| **[contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp)** | MCP server: profile, match and merge a contact export **with the evidence for each match** | Open-source utility |
| **[api-webhook-integration-patterns](https://github.com/skmalikllc/api-webhook-integration-patterns)** | Validation, field mapping, retries, idempotency, HMAC verification — 31 tests, CI green | Technical lab |
| **[data-sync-dedup-reconciliation](https://github.com/skmalikllc/data-sync-dedup-reconciliation)** | The method behind sync, deduplication, reconciliation and migration validation | Method + case index |
| **[google-workspace-apps-script-automation](https://github.com/skmalikllc/google-workspace-apps-script-automation)** | Apps Script repair, extension, and a 617-question form generated programmatically | Sanitized client case studies |
| **[cloud-file-migration-case-studies](https://github.com/skmalikllc/cloud-file-migration-case-studies)** | Provider-to-provider migrations and file architecture, structure intact | Sanitized client case studies |
| **[automation-client-case-studies](https://github.com/skmalikllc/automation-client-case-studies)** | n8n, Make and Zapier builds, plus the jobs that arrive already broken | Sanitized client case studies |
| **[airtable-systems-portfolio](https://github.com/skmalikllc/airtable-systems-portfolio)** | Three completed Airtable client engagements, and how I handle duplicates in a base | Client engagement record |

---

## How I design reliable automations

The part clients actually pay for is not the workflow. It is that the workflow does
not quietly corrupt something at 3am on a Sunday.

1. **Understand source and destination** before touching either.
2. **Define the source of truth** — one system wins, in writing, before the first run.
3. **Map the fields.** Most integration failures are a mapping assumption, not a bug.
4. **Handle duplicates deliberately.** A merge rule decided up front beats a cleanup later.
5. **Validate inputs** rather than trusting that they arrive in the shape they did last month.
6. **Test with controlled data**, not the client's live records.
7. **Verify the result** — count it, compare it, don't assume the tool told the truth.
8. **Handle the exceptions** — and where something is genuinely ambiguous, stop and ask rather than guess.
9. **Document the handover** so it survives without me.

On larger builds this extends to retries, idempotent reruns, logging, alerting, a
human approval step and end-of-run reconciliation — where the engagement warranted
it. I do not claim every historical project had all nine.

---

## Professional background

Two distinct tracks, and they should not be blurred together:

**2003 – 2023 · Technical, operations and training career**
Around twenty years of structured technical, administrative, operations, supervision
and training work, beginning in Pakistan Air Force service. Documentation discipline,
controlled operational environments, fault-finding, and training other people to
follow a process correctly.

**2015 – present · International freelance client services**
Remote delivery for clients in the UK, US, Europe and Australia through Fiverr and
Upwork — 200+ completed engagements.

**Recent specialisation**
Automation, integrations, Google Workspace systems, data migration and AI-assisted
workflows.

That first track is not software engineering, and I do not present it as such. What
it gave me is the habit of writing things down before touching them — which is most
of why migrations I run do not lose files.

```
2003 ──────────────────────────────── 2023
   Technical / operations / training career
                  │
   2015 ──────────────────────────────▶ present
      International freelance client services
                                        │
                              Automation · Integrations
                              Google Workspace · APIs
                              Data migration · MCP tooling
```

---

## Skills

### Primary

The fifteen I am actually hired for:

`n8n` · `Make.com` · `Zapier` · `Google Apps Script` · `Google Workspace` ·
`Google Sheets` · `REST APIs` · `Webhooks` · `Data migration` ·
`Deduplication & reconciliation` · `Airtable` · `Node.js` · `JavaScript` ·
`CSV / data cleanup` · `Model Context Protocol (MCP)`

<details>
<summary><b>Full capability matrix</b> — every group, with the repository that evidences it</summary>

<br>

| Group | Skills | Evidenced in |
|---|---|---|
| **Workflow automation** | n8n · Make.com · Zapier · workflow design · triggers · scheduling · conditional logic · error handling · workflow troubleshooting | [automation-client-case-studies](https://github.com/skmalikllc/automation-client-case-studies) · [n8n-google-contacts-backup](https://github.com/skmalikllc/n8n-google-contacts-backup) · [workflow-automation-patterns](https://github.com/skmalikllc/workflow-automation-patterns) |
| **Google Workspace** | Workspace · Sheets · Apps Script · Drive · Gmail · Contacts · Forms · Docs · Workspace admin troubleshooting | [google-workspace-apps-script-automation](https://github.com/skmalikllc/google-workspace-apps-script-automation) · [gmail-business-inbox-organization](https://github.com/skmalikllc/gmail-business-inbox-organization) · [google-workspace-automation-lab](https://github.com/skmalikllc/google-workspace-automation-lab) |
| **APIs & integrations** | REST APIs · webhooks · JSON · data mapping · request/response troubleshooting · HMAC signature verification · retries · idempotency | [api-webhook-integration-patterns](https://github.com/skmalikllc/api-webhook-integration-patterns) |
| **Data & migration** | data migration · synchronisation · contact sync · deduplication · reconciliation · data cleanup · CSV · Excel · duplicate prevention · file migration · folder architecture | [data-sync-dedup-reconciliation](https://github.com/skmalikllc/data-sync-dedup-reconciliation) · [contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp) · [cloud-file-migration-case-studies](https://github.com/skmalikllc/cloud-file-migration-case-studies) |
| **Databases & client systems** | Airtable · CRM workflows · Jotform · client intake · form workflows · database operations · CRM data cleanup | [airtable-systems-portfolio](https://github.com/skmalikllc/airtable-systems-portfolio) · [jotform-client-intake-automation](https://github.com/skmalikllc/jotform-client-intake-automation) |
| **AI / modern automation** | Model Context Protocol (MCP) · AI-assisted data workflows · tool schemas | [contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp) |
| **Development** | JavaScript · Node.js · Chrome Extensions (MV3) · GitHub Actions · `node:test` · scripting · Python (supporting level) | [table-to-sheets](https://github.com/skmalikllc/table-to-sheets) · [api-webhook-integration-patterns](https://github.com/skmalikllc/api-webhook-integration-patterns) · [contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp) |
| **Cloud & file systems** | Google Drive · OneDrive · Dropbox · Mega · cloud migration · file organisation · folder architecture · migration verification | [cloud-file-migration-case-studies](https://github.com/skmalikllc/cloud-file-migration-case-studies) |
| **Business operations** | documentation · document control · reporting · email management · file management · administrative systems · data management · project coordination · process improvement · client follow-up | [business-operations-systems](https://github.com/skmalikllc/business-operations-systems) · [digital-operations-portfolio](https://github.com/skmalikllc/digital-operations-portfolio) |
| **E-commerce** | Amazon · eBay · Etsy · Shopify · WooCommerce · WordPress · product and catalogue operations · e-commerce administration | [ecommerce-operations-portfolio](https://github.com/skmalikllc/ecommerce-operations-portfolio) |

**Deliberately not claimed**, because no verified completed project exists: HubSpot
migrations or admin · Stripe · Twilio / WhatsApp Business specialisation ·
GoHighLevel migrations · Clay · Attio · WeCom · Formstack · advanced security or
compliance engineering · WordPress plugin or theme development · marketplace API and
inventory-sync automation.

</details>

### Supporting experience

From the technical operations career, and useful rather than headline:

technical training · operations supervision · documentation discipline ·
quality and compliance awareness · fault-finding · preventive maintenance ·
administrative systems

**This is operations and documentation discipline, not software engineering**, and it
is not presented as such anywhere in this portfolio.

---

## Track record

| | |
|---|---|
| **Completed freelance engagements** | 200+ |
| **Fiverr** | 221 completed orders · 100% on-time delivery *(account snapshot, Sep 2026)* |
| **Fiverr rating** | **4.9 ★ from 109 reviews** — 107 five-star, 2 four-star *(verified Sep 2026)* |
| **Upwork** | 100% Job Success · Rising Talent · 5 completed contracts, every one **5.0** |
| **Here** | 19 repositories · 3 of them with tests running in CI on every push |

### What clients said

> "Delivered a clean, efficient solution ahead of schedule."
> — Upwork client · n8n workflow build · Nov 2025

> "Labels, filters, and folders were set up perfectly, saving me a lot of time."
> — Fiverr client, United Kingdom · mailbox organisation · Aug 2026

> "The Jotform was built exactly as requested. Clean layout, smooth functionality."
> — Fiverr client, Germany · client intake form · Aug 2026

> "Drive was organized and really helped me and my team out."
> — Fiverr client, United States · Drive reorganisation · 2025

> "Great to work with. Have done several projects."
> — repeat Fiverr client, United States · Sep 2026

---

## Get in touch

- **Upwork** — [upwork.com/freelancers/skmalik1](https://www.upwork.com/freelancers/skmalik1)
- **Fiverr** — [fiverr.com/skmalik166](https://www.fiverr.com/skmalik166)

Open to short migrations and cleanups, workflow builds, integration work and ongoing
automation support.
