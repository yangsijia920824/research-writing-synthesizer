# Source Corpus Pipeline

## Purpose

Create a complete, searchable, and traceable source document before attempting to draft prose.

## Source Selection

1. Start from a clearly defined manuscript contribution or writing question.
2. Select a focused group of approximately 10-30 directly relevant papers.
3. Favor relevance over prestige, but sorting by journal or source type can make comparison easier.
4. Include contrasting approaches when they help expose the field's argument structure.
5. Record the selection reason for each source.

The number is a working range, not a quota. Stop adding papers when new items no longer change the argument map or supply necessary evidence.

## Extraction Procedure

For every selected paper:

1. Store the full citation and a stable identifier.
2. Add a visible article heading.
3. Copy the complete target section, commonly the introduction.
4. Include the next section heading or another boundary marker when needed to prove completeness.
5. Preserve article order and paragraph boundaries.
6. Keep tables, equations, subscripts, and special formatting when they carry meaning.
7. Avoid spending time on cosmetic cleanup during extraction.

Completeness matters because truncated passages hide transitions, caveats, and the paper's actual closing move.

## Corpus Record

Use a record such as:

```text
Source ID:
Full citation:
Persistent identifier:
Selection reason:
Section:
Boundary verified:
Source text:
```

For a document-based workflow, keep one source document containing all records. For a structured workflow, use equivalent fields in a table or database.

## Integrity Checks

- The expected and extracted paper counts match.
- Every paper has citation metadata and a visible boundary.
- No article ends mid-sentence or mid-paragraph because of extraction failure.
- The intended section title is present.
- Duplicate imports are identified without deleting useful variants prematurely.
- Source order and paragraph breaks remain recoverable.
- Encoding or OCR errors affecting scientific meaning are flagged.

## Incremental Use

The corpus may be expanded later. Mark the end of currently labeled material explicitly so newly added or previously skipped passages can be revisited without relabeling the entire collection.
