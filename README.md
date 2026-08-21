# Vascue agent skills

[Agent Skills](https://agentskills.io) for working with [Vascue](https://www.vascue.io), the operational spine for healthcare providers: an AI front desk for patient communication and booking, and claims automation for provider-side insurance claims.

These are the same skills Vascue serves from its website at
`https://www.vascue.io/.well-known/agent-skills/index.json`; this repository exists so that
`npx skills add vascue-io/skills` and the skills directories can index them.

## Skills

| Skill | Use it when |
| --- | --- |
| [`vascue-site`](skills/vascue-site/SKILL.md) | An agent needs public information about Vascue: products, insurance claims automation, clinical document processing, patient communication, integrations, case studies, security, pricing, contact details. |
| [`evaluate-vascue-claims-automation`](skills/evaluate-vascue-claims-automation/SKILL.md) | A clinic, hospital, or other provider is evaluating whether Vascue Claims fits a repetitive, document-heavy insurance workflow. |

## Install

```bash
npx skills add vascue-io/skills
# or one skill only
npx skills add vascue-io/skills --skill vascue-site
```

## Machine-readable companions

- `https://www.vascue.io/llms.txt`
- `https://www.vascue.io/openapi.json` (public read-only content surface)
- `https://www.vascue.io/.well-known/mcp/server-card.json` (public knowledge-search MCP server)

Public content only. Never send patient information, claim documents, clinic credentials, or booking requests to any of these surfaces.
