# Contributing

Thanks for helping improve this list! Suggestions are welcome through pull requests or issues.

## What belongs here

- Projects, tools, papers and learning resources that are **built on or directly support Isaac Lab** (including Orbit, its predecessor).
  Multi-simulator projects are welcome when Isaac Lab is a supported backend.
- Projects that are public and maintained. Archived repositories and repositories with no activity in the last 18 months are usually not added.
- Papers need public code that uses Isaac Lab or Orbit.

## How to add an entry

1. Pick the most specific section. Within a section, keep the existing order.
2. Use the same format as the neighboring entries:

   ```markdown
   - [Name](https://github.com/owner/repo) — One neutral sentence on what it is and which robots or tasks it covers.
   ```

   For papers:

   ```markdown
   - **Paper Title** (Venue Year) [[paper]](https://arxiv.org/abs/XXXX.XXXXX) [[code]](https://github.com/owner/repo)
   ```

3. Keep descriptions short and factual: no marketing language, no emoji.
4. One pull request per addition makes review faster.

The link checker runs on every pull request and weekly on `main`. If an entry's link breaks for good, it will be removed.
