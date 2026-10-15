# Library Guide

**Project:** Internal IT Help Desk – Prompt Library  
**Owner:** Hajar Alanazi
**Version:** v1  
**Date:** 2026-10-15

## Purpose

This guide explains how to use the five IT Help Desk prompt templates safely and correctly.

## How to Use: Pick, Fill, Run, Review

1. **Pick:** Choose the appropriate template from `library_index.md`.
2. **Fill:** Replace the variables with the required information using fictional or masked data.
3. **Run:** Copy the completed prompt into ChatGPT.
4. **Review:** Check the generated response against the approved IT facts and the CHECK section before using it.

## Available Templates

| Template | Purpose |
|---|---|
| IT-Resolve-Ticket | Write a clear reply to an IT support ticket |
| IT-Summarize-Ticket | Summarize a ticket conversation into three lines |
| IT-Route-Tickets | Classify a ticket and identify the reason and next step |
| IT-Explain-Answer | Simplify a technical answer for an employee |
| IT-Translate-Status | Translate service messages between Arabic and English |

## Variables

| Variable | Description |
|---|---|
| `[INPUT_TEXT]` | The ticket, conversation, answer, or message |
| `[LANGUAGE]` | Arabic, English, Automated, Bilingual, or Mixed |
| `[TONE]` | Neutral, Formal, Polite, or Calm |
| `[MAX_WORDS]` | Maximum number of words |
| `[FACTS]` | Approved IT Help Desk facts |
| `[CATEGORIES]` | Access, Hardware, Software, Network, Other |

Use only the variables required by the selected template.

## Example

**Template:** IT-Resolve-Ticket-v1

**Filled variables:**

- INPUT_TEXT: I forgot my password. How can I reset it?
- LANGUAGE: English
- TONE: Polite
- MAX_WORDS: 60
- FACTS: IT-Facts-v1

**Expected response:**

Dear employee,

You can reset your password only through the self-service portal.

The CHECK section is added separately for the reviewer.

## Quality Checklist

Before using an output, verify that:

1. All information is supported by the approved IT facts.
2. Dates, times, numbers, and names are accurate.
3. No unsupported promises or actions are included.
4. No sensitive personal information is repeated.
5. The response is complete, clear, and follows the requested format.

## Responsible Use

- Never enter real passwords or verification codes.
- Use masked information such as `User-1` or `Request-X`.
- Do not invent IT support procedures.
- Do not treat AI-generated responses as completed actions.
- A human technician must review outputs before sending them.

## Shared Files

- `blocks/IT-Facts-v1_2026_10_15.md` – IT Help Desk facts.
- `rules/IT-Rules-v1_2026_10_15.md` – Responsible-use rules.
- `Test_Results_Report.pdf` – Test results and evaluation evidence.

## Note

All examples are fictional and intended for training. Replace the training facts with officially approved organizational information before real use.

## Change Log

| Version | Date | Change |
|---|---|---|
| v1 | 2026-10-15 | First version of the IT Help Desk library guide |