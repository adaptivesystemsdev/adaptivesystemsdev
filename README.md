### Adaptive Systems: deterministic AI infrastructure

We build AI products where **the model reads and code decides**: every fact comes from config or from the
page, every decision is a check you can audit, and every number we publish was measured on the live system.
Three products run in production on our own server, and we build custom AI systems for clients to the same
standard. [adaptivesystems.dev](https://adaptivesystems.dev)

| Product | What it does | Case study · try it |
|---|---|---|
| **Front Desk** | AI receptionist for service businesses: voice agent (browser or a real phone number), website chat with a call button, Telegram, grounded support answers, Google Calendar booking, lead scoring behind a deterministic gate, one inbox for every channel | [ai-command-center](https://github.com/adaptivesystemsdev/ai-command-center) · [live numbers](https://adaptivesystems.dev/live#front-desk) · [score a lead](https://adaptivesystems.dev/platform/try) |
| **Docket** | Invoice and document intake for Europe and the US: every value traced to the page it came from (PDFs, scans and phone photos, read twice by a vision model and OCR), arithmetic / IBAN / US routing / VAT checked in code, a risk gate for bank-detail fraud (IBAN or ACH), duplicates and PO mismatches | [docket-invoice-intake](https://github.com/adaptivesystemsdev/docket-invoice-intake) · [live numbers](https://adaptivesystems.dev/live#docket) · [try your invoice](https://adaptivesystems.dev/docket/try) |
| **Dossier** | Applicant document verification for lenders, letting agents and AML-regulated firms: bank statements, bills, payslips and IDs read by a model; code finds edits inside the PDF (before → after), text hidden under boxes, retyped amounts, broken balances and bad MRZ check digits, and compares every name, address and date with the declaration. Checks documents, never scores people | [dossier-applicant-verification](https://github.com/adaptivesystemsdev/dossier-applicant-verification) · [live numbers](https://adaptivesystems.dev/live#dossier) · [forge an applicant](https://adaptivesystems.dev/dossier/try) |

All three on one page: **[the one-pager](https://adaptivesystems.dev/one-pager)** (what they do, how they decide, measured numbers, stack, links).
Docket and Dossier also work inside Claude: **[connect the MCP server](https://adaptivesystems.dev/mcp)** (OAuth, a sandbox of your own, erased after 30 minutes).

**Hire us for a custom build:** assistants on your data, document pipelines, voice and chat agents, decision
engines, n8n automations and integrations, or a rescue of a bot that misbehaves. Scoped and quoted before work
starts, weekly demos, tests and a written handover. [Tell us what to build](https://adaptivesystems.dev/contact?topic=custom) ·
[Upwork](https://www.upwork.com/freelancers/~01e6b54c0e8f04bcaa)

Live: [status page](https://status.adaptivesystems.dev/status/stack) · [activity feed](https://adaptivesystems.dev/live)

<sub>Python · FastAPI · Pydantic AI · LangGraph · TypeScript · PostgreSQL / pgvector · Next.js · n8n · ElevenLabs · PDF forensics · OCR · Docker · self-hosted</sub>
