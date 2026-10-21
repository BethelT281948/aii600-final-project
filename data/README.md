# Data

The files the notebook reads are assets on the GitHub release tagged `data`. They are not committed. From the project root, after the files are in this folder:

```bash
gh release create data data/your-file.csv --title "Data" --notes "See data/README.md"
```

Add every file the notebook reads. The release is public, like the fork. Replace the lines below.

- Source.
- File names on the `data` release.
- Unit of observation, sample size, and time span.
