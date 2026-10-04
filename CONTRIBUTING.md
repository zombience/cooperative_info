# Adding to this repo

Everyone in the group is welcome to add links, notes, and corrections.

## Adding a link
1. Pick the right page in [`docs/resources/`](docs/resources/).
2. Add a row with: the link (with its real title), who published it, and **one or two sentences on why it's useful to us**. An annotation is what makes a link list worth more than a search.
3. If it's beginner, intermediate, or advanced, tag it 🟢, 🟡, or 🔴.
4. If it fits a learning-path step, link it from that step's "Read" section too.

## Recording a decision
Add it to the top of the [decision log](docs/worksheets/decision-log.md) using the template.

## Ground rules
- **`docs/` is public.** Everything under `docs/` is published to the public website when merged. Member-only notes go in [`private/`](private/), which is never published.
- **No personal financial details**, account numbers, or private documents. Keep those somewhere private.
- Don't paste documents from our lawyer into `docs/`. If the group agrees, they can go in `private/`.
- Prefer primary sources (statutes, official program pages, the original article) over summaries.
- If a link breaks or a program ends, fix or remove it and note the date.

## Editing on GitHub without git
Open any file, click the pencil icon, make your change, and choose "Create a new branch and start a pull request." On the website, the pencil icon at the top of each page takes you straight to that file. Before merging, the reviewer checks one thing above all: **nothing private is going into `docs/`.** An automatic check also builds the site and flags broken internal links.

## Adding a new page
Create the `.md` file under `docs/`, then add it to the `nav:` list in `mkdocs.yml` so it appears in the menu.
