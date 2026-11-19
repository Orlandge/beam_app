- After each request, add an entry to prompts.md: what I asked, what you changed, and whether it worked.
- After completing and validating a task that changes project files, create a local git commit with a concise, descriptive message. Stage only changes made for that task; do not include unrelated changes. Do not push unless explicitly asked. If validation fails, do not commit until the issue is resolved or the user approves proceeding.

# Project layout

Keep these project files at the repository root:

- `AGENTS.md` — project instructions.
- `spec.md` — the project specification.
- `prompts.md` — a log of requests, changes, and outcomes.
- `index.html` — the single-file web app entry point; it must stay at the root for GitHub Pages.

Put all other new files in the numbered folder that best fits their purpose. Do not add miscellaneous files to the root.

- `00_planning/` — notes and sketches.
- `01_data/` — data files.
- `02_validation/` — hand calculations and test cases.
- `03_output/` — screenshots and exported results.

