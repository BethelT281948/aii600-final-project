# Data

The files the notebook reads are assets on the GitHub release tagged `data`. They are not committed. The release is public. If the data cannot be public, choose different data.

`OWNER/REPO` is your fork, the form `username/aii600-final-project`. In the clone, once:

```bash
gh repo set-default OWNER/REPO
```

Create the release from the project root, after the files are in this folder:

```bash
gh release create data data/your-file.csv --repo OWNER/REPO --title "Data" --notes "See data/README.md"
```

Add every file the notebook reads. When a file changes:

```bash
gh release upload data data/your-file.csv --repo OWNER/REPO --clobber
```

On another machine:

```bash
gh release download data --dir data --repo OWNER/REPO
```

Replace the lines below.

- Source.
- File names on the `data` release.
- Unit of observation, sample size, and time span.
