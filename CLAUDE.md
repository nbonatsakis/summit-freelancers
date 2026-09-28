# summit-freelancers

<!-- impeccable:start -->
## Design quality (Impeccable)

Impeccable is installed at project scope (`.claude/skills/impeccable`, agents in `.claude/agents/impeccable-*.md`). Its design hook runs after every Edit or Write on UI files and does a deeper pass when a turn ends. Treat its findings as part of the task.

- Run `/impeccable init` once to write `PRODUCT.md` (audience, purpose, platform, brand commitments), then `/impeccable document` to capture the existing visual system in `DESIGN.md`. Keep both current. When a result feels generic, fix the context first.
- For new pages or sections, start with `/impeccable shape` or describe the page to `/impeccable`. Prefer it over the generic `frontend-design` skill here, because it reads this project's context.
- To refine existing pages, run `/impeccable critique <page>` to find problems, then `polish`, `typeset`, `layout`, `colorize`, `distill`, `clarify`, `bolder`, or `quieter` on that page.
- Before shipping a visible change, run `/impeccable audit <page>` (accessibility, performance, responsive behavior).
- Project rules elsewhere in this file (SEO, content structure, analytics or affiliate markup) take precedence over design suggestions.
<!-- impeccable:end -->
