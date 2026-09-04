# Repository conventions

- This repository collects UI component sources for reference.
- Keep upstream repositories as Git submodules under `references/` and record their exact commits in the parent repository.
- Preserve upstream source, licenses, and attribution. Do not edit reference checkouts or move their pinned commits unless the task requires it.
- Update `README.md` when adding, removing, or changing a reference or its setup instructions.
- Keep edits minimal, propagate unexpected errors, and do not add dependencies or test scaffolding for repository bookkeeping.
