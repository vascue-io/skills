---
name: vascue-site
description: Navigate Vascue's public healthcare-operations website. Use when an agent needs public information about Vascue, insurance claims automation, clinical document processing, patient communication, clinic integrations, case studies, security, pricing, or contact details.
license: CC-BY-4.0
metadata:
  author: vascue-io
  version: "1.0"
  homepage: https://www.vascue.io
---

# Navigate the Vascue public site

Use only public information. Do not submit forms or treat marketing pages as an
authenticated service API.

## Start here

- Company and machine-readable overview: https://www.vascue.io/llms.txt
- Public knowledge-search MCP server: https://www.vascue.io/mcp/search
- MCP server card: https://www.vascue.io/.well-known/mcp/server-card.json
- Claims automation brief: https://www.vascue.io/claims-automation.md
- Products: https://www.vascue.io/products
- Case study: https://www.vascue.io/customers/radiology-hong-kong
- Security: https://www.vascue.io/security
- Contact: https://www.vascue.io/contact-us

Request a public HTML page with `Accept: text/markdown`, or append `.md`, when
a concise Markdown representation is preferable.

Use the public knowledge-search MCP server when a question spans several Vascue
pages or the most relevant page is unknown. Its index contains public website
content only. Never send patient information, claim documents, clinic
credentials, or booking requests to the search tool.

Agent-based clinic booking is a research pilot, not a live public booking API.
Do not send patients, credentials, or booking requests to the research page.
