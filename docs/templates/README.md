# Templates

This directory exists in the BUS-629 course tree as a **structural example** — it shows where templates live in a project repo so you can mirror the same layout in your own portfolio repo.

## The canonical templates live at the repo root

To avoid drift, BUS-629 does not maintain its own copies of the memo and spec templates. The single source of truth is at the repository root:

- **Memo template:** [`../../../../docs/templates/memo-template.md`](../../../../docs/templates/memo-template.md)
- **Spec template:** [`../../../../docs/templates/spec-template.md`](../../../../docs/templates/spec-template.md)
- **Prompt log:** [`../../../../docs/templates/prompt-log-template.md`](../../../../docs/templates/prompt-log-template.md)
- **Portfolio (bio + resume):** [`../../../../docs/templates/portfolio/`](../../../../docs/templates/portfolio/)
- **Templates README** (frontmatter schema, naming conventions): [`../../../../docs/templates/README.md`](../../../../docs/templates/README.md)

When the underlying templates evolve, every course inherits the change automatically.


## YAML frontmatter

Every template has a YAML frontmatter block declaring `template`, `purpose`, `audience`, `fields_required`, and `naming_convention`. When you adapt a template, keep the frontmatter intact — tooling (and the LLM-spec workflow at Stage 4) reads it.