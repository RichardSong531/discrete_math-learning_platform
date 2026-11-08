# Contributing

## Workflow

Edit `modules/<topic>/index.html` directly. Keep modules standalone while developing
the curriculum; no package manager or frontend build is required. Use stable topic
paths and Git history instead of versioned filenames.

New modules should include their HTML, scope/prerequisite README, references file,
and coverage report recording actual checks and remaining limitations.
Update the root topic guide and totals, shared navigation in every available map,
the root README, curriculum handoff, product status, and reference register. Update
the learning model when behavior changes. Keep module navigation descriptions current;
prefer linking to the root guide over repeating the total number of available maps.
Document provenance and unresolved content questions. Do not add empty directories
for planned topics.

## Manual checks before committing

- Serve the repository and load each changed module.
- Inspect the browser console, graph, and selected-node lessons.
- Try a lab, correct and incorrect answers, and a mastery check.
- Check invalid lab inputs and incomplete or repeated quiz submissions.
- Try Recommended next, Mixed Practice, and Cheat Sheet search.
- Reload to check saved progress; test Reset in a disposable browser profile.
- Check recovery from malformed or unavailable browser storage.
- Where written drafts exist, check reload, independent resets, and printing.
- Check keyboard navigation and a narrow viewport.
- Follow the root guide and previous/next topic links; check local documentation links.
- Verify changed mathematics and answer keys against recorded sources.
- Run `git diff --check` and review for unintended changes or personal data.

These are acceptance checks, not an existing automated browser test suite. State which
checks were actually performed. Keep commits scoped to genuine milestones.

## Git identity

Configure identity locally in each repository and verify it before committing:

```sh
git config --local user.name "RichardSong531"
git config --local user.email "127546276+RichardSong531@users.noreply.github.com"
git var GIT_AUTHOR_IDENT
git var GIT_COMMITTER_IDENT
```

Use an email associated with the intended GitHub account. Do not change global identity
as part of repository work.
