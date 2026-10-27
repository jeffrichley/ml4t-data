# ml4t-data

Course data archives for CS7646 Machine Learning for Trading.

Students don't download these by hand: `uv run ml4t data` in a Student Repo
fetches the archive pinned by the installed `ml4t-harness`, checks its SHA-256
against the pinned value, and unpacks it into the repo's `data/` folder.

## Releases

- `test`: a small stand-in archive (6 symbols, 2008-06 to 2009-03) used until
  the full course archive is released.
