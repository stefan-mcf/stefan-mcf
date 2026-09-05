# Stefan McFeeters

I design and build operational software, integrations and automation through [SM Systems](https://smsystems.au/).

I take on scoped business projects and agency subcontracting, covering implementation, testing and handover. My work spans custom software, customer-facing websites, CRM and support systems, cloud services, and connected RFID/edge systems. Ongoing work can cover improvements, integrations and an agreed delivery backlog.

My main tools are Python, TypeScript, C#/.NET, FastAPI, PostgreSQL and AWS, alongside Zendesk, Jira, HubSpot, Airtable, Make and n8n.

For a project or agency subcontract, email [stefan@smsystems.au](mailto:stefan@smsystems.au) with what exists, what needs to work better and your timeframe.

## Selected projects

### [RFID Subscription and Access Platform](https://github.com/stefan-mcf/rfid-subscription-access-system)

Client systems implementation connecting customer accounts, per-vehicle subscriptions, local RFID access decisions and operator controls. I designed and implemented the application, cloud and edge integration. Stripe remains in sandbox and staged physical commissioning remains. The public repository contains architecture and a reference model; client source stays private.

`.NET` `PostgreSQL` `AWS` `SQLite` `RFID` `OPC UA`

### [Precision Residential Construction Website](https://github.com/stefan-mcf/precision-residential-construction)

Live paid-client website for a Geelong residential builder. I handled discovery, content, design, implementation and launch, including responsive project content, direct contact paths and structured quote intake. [Visit the client site](https://prconstruction.au/).

`HTML` `CSS` `JavaScript` `n8n`

### [Conversion Measurement and Inbound Lead System](https://github.com/stefan-mcf/conversion-measurement-inbound-lead-system)

SM Systems' own enquiry and measurement implementation connecting the website, GTM/GA4, HubSpot, Airtable and Make. I built the shared submission reference, human qualification controls and Playwright checks, including a retained duplicate-event regression.

`Playwright` `GTM` `GA4` `HubSpot` `Airtable` `Make`

### [Airtable and Make Opportunity Pipeline](https://github.com/stefan-mcf/airtable-make-opportunity-pipeline)

Internal opportunity and delivery system for approved intake, duplicate control, exceptions and accepted project handoff. My work covers the data model, routing controls and operator workflow; the connected router was returned to inactive after testing.

`Airtable` `Make` `JSON contracts`

### [API Webhook Bridge](https://github.com/stefan-mcf/api-webhook-bridge)

Local reference implementation for validating events, mapping fields and preventing duplicate downstream operations. I built the FastAPI service, audit/dead-letter controls, tests and operating documentation. Its supplied scenarios use local provider-shaped contracts.

`Python` `FastAPI` `OpenAPI` `pytest`

### [Zendesk AI Support Copilot](https://github.com/stefan-mcf/zendesk-ai-support-copilot)

Internal support system with grounded retrieval, cited private suggestions, human approval and a verified Zendesk-to-Jira handoff. My work spans discovery, backend, evaluation, frontend and AWS delivery. Controlled AWS commissioning is documented; the temporary runtime was decommissioned after closeout.

`Python` `FastAPI` `React` `PostgreSQL` `AWS Bedrock` `Zendesk` `Jira`

## Operations and workflow systems

| Project | Focus |
| --- | --- |
| [HubSpot Lead-to-Deal CRM](https://github.com/stefan-mcf/hubspot-lead-to-deal-crm) | Linked company, contact and deal records with a seven-stage operating pipeline and idempotent lifecycle controls. |
| [HubSpot to Zendesk Customer Handoff](https://github.com/stefan-mcf/hubspot-zendesk-customer-handoff) | Approval-gated CRM-to-support mapping, stable external IDs and provider readback using controlled commissioning records. |
| [n8n Service Lead Routing](https://github.com/stefan-mcf/n8n-service-lead-routing) | Importable 20-node workflow covering accepted, duplicate, invalid, review and integration-exception outcomes. |
| [Airtable Coaching Program Delivery Hub](https://github.com/stefan-mcf/airtable-coaching-program-delivery-hub) | Linked participants, coaching plans and sessions with owner and role-specific Airtable Interfaces. |
| [Zendesk to Jira Support Escalation](https://github.com/stefan-mcf/zendesk-jira-support-escalation) | Guarded provider-native trigger, webhook mapping and destination reconciliation. |

## Supporting tools

| Repository | Focus |
| --- | --- |
| [Shopify Revenue Leak Auditor](https://github.com/stefan-mcf/shopify-revenue-leak-auditor) | Browser-based product-page audits with evidence capture, weighted findings and client-ready Markdown and HTML reports. |
| [Automation Debugger](https://github.com/stefan-mcf/automation-debugger) | Failure diagnosis, deterministic corrections and guarded local replay for automation events. |
| [Sheets Airtable Sync](https://github.com/stefan-mcf/sheets-airtable-sync) | Row normalisation, reconciliation, exception routing and Airtable upsert planning. |
| [Invoice Router](https://github.com/stefan-mcf/invoice-router) | Invoice extraction, validation, review routing and accounting export preparation. |
| [Review Router](https://github.com/stefan-mcf/review-router) | Typed policy gates, confidence metadata and human review through CLI and API surfaces. |
| [Automation Kit](https://github.com/stefan-mcf/automation-kit) | Reusable Python, FastAPI, OpenAPI, Docker and low-code workflow patterns. |
| [Browser Research](https://github.com/stefan-mcf/browser-research) | Browser-based source extraction, evidence scoring and structured research output. |

I’m also completing a Bachelor of Artificial Intelligence in Melbourne, Australia.

[Portfolio](https://smsystems.au/) · [LinkedIn](https://www.linkedin.com/in/stefan-mcfeeters/) · [Email](mailto:stefan@smsystems.au)
