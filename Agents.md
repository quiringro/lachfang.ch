This is an existing website project. Modify the current codebase incrementally.

Rules:
- Never rewrite the whole app or replace a full file unless explicitly asked.
- Preserve existing structure, content, and styling.
- First inspect the codebase and identify the relevant files.
- Prefer minimal diffs and targeted edits.
- When adding a feature, integrate it into the existing layout rather than generating a new page.
- If a file seems ambiguous, explain which file you chose and why.
- Before finishing, summarize changed files and what was changed in each.
- Do not delete unrelated code.
- If asked to add a UI component like a header, footer, or section, keep the rest of the page intact.
- For homepage edits, first look for: app/page.tsx, pages/index.tsx, src/App.tsx, index.html, or layout/header components.
- Reuse existing CSS/classes/components where possible.
- Do not introduce a new framework or redesign the entire page unless explicitly requested.
