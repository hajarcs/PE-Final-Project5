# Library Index

| Template | Task | Variables | Version | Status |
|---|---|---|---|---|
| [IT-Resolve-Ticket](templates/IT-Resolve-Ticket-v1_2026_10_15.md) | Resolve a support ticket | [INPUT_TEXT], [LANGUAGE], [TONE], [MAX_WORDS], [FACTS] | v1 | Approved |
| [IT-Summarize-Ticket](templates/IT-Summarize-Ticket-v1_2026_10_15.md) | Summarize a ticket thread for the next technician | [INPUT_TEXT], [LANGUAGE], [TONE], [MAX_WORDS], [FACTS] | v1 | Approved |
| [IT-Route-Tickets](templates/IT-Route-Tickets-v1_2026_10_15.md) | Classify a support ticket | [INPUT_TEXT], [CATEGORIES], [LANGUAGE], [FACTS] | v1 | Approved |
| [IT-Explain-Answer](templates/IT-Explain-Answer-v1_2026_10_15.md) | Rewrite a technical answer in plain language | [INPUT_TEXT], [LANGUAGE], [TONE], [MAX_WORDS], [FACTS] | v1 | Approved |
| [IT-Translate-Status](templates/IT-Translate-Status-v1_2026_10_15.md) | Translate a service status message between Arabic and English | [INPUT_TEXT], [LANGUAGE], [TONE], [MAX_WORDS], [FACTS] | v1 | Approved |

## Shared blocks

| Block | Used by | File |
|---|---|---|
| IT Facts (v1) | All five templates | `blocks/IT-Facts-v1_2026_10_15.md` |

## Rules

| File | What it is |
|---|---|
| `rules/IT-Rules-v1_2026_10_15.md` | Five responsible-use rules for the Internal IT Help Desk |

## [LANGUAGE] values

| Value | Meaning |
|---|---|
| Arabic | Answer in Arabic only |
| English | Answer in English only |
| Automated | Use the appropriate language based on the input |
| Bilingual | Two separate versions: Arabic, then English |
| Mixed | One response combining Arabic and English |

## Change Log

| Version | Date | Change |
|---|---|---|
| v1 | 2026-10-15 | First version of the Internal IT Help Desk prompt library index |