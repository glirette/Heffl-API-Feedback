# Heffl API Observations - 2026-06-15

## Confirmed Working

### v2 Task Assignment

Synthetic task assignment to the Terrianne operator user worked with v2 task creation and `assigneeIds`.

Evidence retained internally:

- Synthetic task: `NG Synthetic v2 Terrianne Assignment proof`
- Purpose: verify `assigneeIds` assignment support for Terrianne operator task routing.
- Customer data: none.

### v2 Operator Queue Task Assignment

Synthetic operator-queue task creation worked with the intended owner set to the Terrianne Heffl user.

Evidence retained internally:

- Task title: `NG internal_test: Synthetic operator queue Heffl v2 native assignment smoke test`
- Candidate ID: `oq_seed_0ea2bbfeb6694a808d9396345d95ac1e`
- Customer data: none.

### v2 Deal Linked Task

Synthetic task linking to a synthetic Heffl deal worked.

Evidence retained internally:

- Task title: `NG internal_test: Synthetic operator queue task linked to Heffl v2 synthetic deal`
- Candidate ID: `oq_seed_587f02e9d5a4477b8fd1fc12e498945f`
- Customer data: none.

## Watch Items

These are not confirmed bugs. They are items to verify before reporting upstream.

- Confirm Heffl v2 task-list filters consistently accept bracketed query parameters such as `filters[assigneeIds][operator]` and `filters[status][values][]`.
- Confirm whether task status values are stable public constants or should be discovered/configured.
- Confirm whether API error responses always use an `error` object with `code`, `message`, and optional `details`.

