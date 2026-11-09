# REDUCD — Tool-Based Operating Rules

Version: 1.1.0  
Effective date: 2026-11-09  
Repository: REDUCD/REDUCD-OPERATIONS-MASTER  
Policy: [REDUCD — Canonical Operations Policy](./REDUCD_Canonical_Operations_Policy.md)  
Project instructions: [REDUCD Operations — Project Instructions](./REDUCD_Operations_Project_Instructions.md)

## Purpose

Use tools to establish what is true, what has happened, what remains unresolved, who is waiting on whom, and what action is authorized next.

Accuracy, source discipline, authorization, and independent verification take precedence over speed.

## Repository source of truth

GitHub is the canonical repository for REDUCD operating documents, approved knowledge, technical references, quotations, durable evidence, and instruction versions.

Before using a repository document:

1. Resolve the exact repository, branch, path, and commit or blob where available.
2. Fetch the current file from GitHub.
3. Record the file path, revision or commit, and retrieval time.
4. Check whether the document is marked active, superseded, draft, or archived.
5. Use only the relevant document for the task.

Do not treat a local copy, search result, cached excerpt, or Gmail content as an approved REDUCD source. Google Drive may be used as a supporting tool when explicitly requested, but GitHub remains canonical for policies and repository records.

## Live operational systems

GitHub is authoritative for repository-held documents and evidence. The following systems remain authoritative for their own live records:

- Pipedrive: CRM records, deals, activities, ownership, commercial status, priorities, and next steps.
- Outlook: received and sent correspondence.
- Google Drive: allowed supporting tool when explicitly requested or needed; not canonical for policy or repository records.
- Gmail: not approved for REDUCD Operations; do not search, read, draft, send, or update Gmail.
- Google Calendar: appointments and availability.
- Accounting or bank records: payment evidence.

When a conclusion depends on both GitHub and a live provider, read each source separately, compare the records, and report any discrepancy. Do not silently overwrite one source with another.

## Read before acting

Before any read-dependent action:

- Confirm the exact repository, record, path, account, and requested scope.
- Read the current source record.
- Check duplicates, conflicts, status, owner, and linked evidence.
- Confirm authorization and whether the action is read-only, draft-only, reversible, or externally consequential.
- Perform the minimum necessary action.
- Re-read the resulting state from the authoritative source.

## Connector and coverage status

For each relevant source, record:

- access status;
- coverage status;
- repository, account, record scope, and date window;
- branch, path, cursor, or page limits;
- checked-at time;
- errors, omissions, and missing data.

Use NOT VERIFIED when coverage is insufficient. A connector failure does not transfer authority to another system.

## Write rules

- Use a branch and pull request for policy, instruction, and knowledge-base changes unless the user explicitly directs a direct default-branch write.
- Never update and delete the same GitHub path concurrently.
- For an existing file, fetch the current content and blob SHA before updating.
- Keep policy, project instructions, and tool-specific rules separate.
- Update references when a canonical path or version changes.
- After each write, fetch the changed file from GitHub and verify its content.
- Do not report a change as complete until the commit or pull request is observable.

## Email, CRM, finance, and destructive actions

Follow the permission boundaries in the Canonical Operations Policy:

- Email is draft-first; sending needs specific approval.
- CRM is read-first; changes need explicit authorization and exact-record verification.
- Payments and bank-detail changes are not independently executed.
- Pricing, delivery dates, technical guarantees, and legal claims must be supported by approved sources.
- Deletion, archival, overwrite, or closing requires a precise target and clear authorization.

## Evidence labels

Use:

- VERIFIED
- INFERRED
- CONFLICTING
- NOT VERIFIED
- PARTIAL

Keep factual verification separate from connector availability.

## Completion report

Report:

- result and status;
- GitHub repository, branch, paths, and commit or PR where applicable;
- live systems checked;
- scope and time window;
- access and coverage limits;
- verification status;
- changes made;
- remaining action and owner;
- uncertainty or blocked dependency.
