# Repository Naming Convention

## Format

```
[vertical]-[use-case]-[type]
```

## Examples

| Repository name | Meaning |
|---|---|
| `hls-claims-automation` | Healthcare, claims processing automation |
| `pharma-complaint-classifier` | Pharma, complaint defect classification |
| `shared-doc-understanding` | Cross-vertical reusable Document Understanding utilities |
| `core-agent-templates` | Agent Builder starter templates |

## Rules

- **All lowercase, hyphens only** — no underscores, no camelCase, no spaces
- **Valid vertical prefixes**: `hls`, `pharma`, `payer`, `healthtech`, `shared`, `core`
- **Max 40 characters** — keep names concise and scannable
- **No generic names** — names like `test`, `automation1`, `myproject`, `repo1` are not allowed
