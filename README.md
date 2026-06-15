# Heffl API Feedback

This repository tracks GoodWare LLC / Notary Geek observations while integrating with the Heffl API.

The goal is constructive: document reproducible API behavior, confirm working patterns, and prepare clear feedback that can help Heffl and GoodWare work well together.

## Current Status

As of 2026-06-15:

- Heffl v2 task assignment using `assigneeIds` is working in synthetic no-customer-data tests.
- Heffl v2 task linking to a synthetic deal using `entity = deals` and `entityId` is working in synthetic no-customer-data tests.
- A Notary Geek / GoodWare internal work-surface endpoint is being deployed to list assigned Heffl v2 tasks safely.
- No confirmed Heffl bug is currently filed here.

## Reporting Rule

Open an issue only when it is one of these:

- Confirmed bug with reproduction steps.
- API behavior that differs from public Heffl docs.
- Documentation gap that caused integration uncertainty.
- Feature request that would materially improve safe operator workflow.

Do not include:

- API keys, tokens, passwords, function keys, publish profiles, or connection strings.
- Customer names, documents, IDs, Persona media, payment data, raw webhook bodies, or private messages.
- Raw vendor payloads unless they are fully synthetic and clearly labeled.

## Tone

Assume good faith. Issues should be clear enough for a Heffl engineer or support person to reproduce without needing private GoodWare context.

