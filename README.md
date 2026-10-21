# AII 600 final project

Fork this repository once per project. The fork tracks the code and the documents. The documents are the proposal, the presentation, and `decisions.md`, which is the history of what was done and why.

Follow the [final project lab](https://vsokolov.org/labs/final-project-lab.html) from the question through the decision to the one-slide summary. The strawberry harvest on that page is the worked example. Your project is your own hypothesis, your own data, and a decision someone will make differently because of the model. `CHECKLIST.md` is the lab's "In your project" boxes.

## Who

Alone, or a group of at most three. One person forks. That person adds the other members as collaborators with Write access, and adds `VadimSokolov` with Read access. On the fork, write the names and GitHub usernames under this heading. One person speaks at the presentation. Every member can explain the whole repository.

## Fork

The repository is public, and so is the fork.

1. Fork https://github.com/VadimSokolov/aii600-final-project.
2. On the fork, open Settings, then General, then Features, and turn Issues on.
3. Settings, then Collaborators. Add teammates with Write access. Add `VadimSokolov` with Read access.
4. Clone the fork. Do the work on `main` and merge before the deadline. A branch that has not been merged is not submitted.
5. The invitation to `VadimSokolov` expires after seven days. Send it before 28 October.

Feedback comes back as an issue on the fork, labeled `proposal`, `preliminary`, or `final`.

## Changes

`main` is the submitted project, and it stays runnable. A person working alone may commit to `main`. A group does not. Branch from `main`, make one change, and open a pull request. Another member reads it and merges it. The request names the `decisions.md` entry it carries out, and that entry is part of the same merge. The commit message says why. Do not force-push `main`.

Two people do not edit `analysis.ipynb` on two branches at once. A function you both change goes in a `.py` or `.R` file, and the notebook calls it. Before a checkpoint merge, run the notebook from the top and commit it with the outputs saved. Save the plots in `fig/`.

`requirements.txt`, or `renv.lock` for R, lists the packages the notebook imports, with versions. Do not commit data files, secrets, or fitted weights. A key stays in `.env`. Data goes on the release tagged `data`, and that release exists by 18 November. A weight file the talk needs goes on a release. If a result depends on a random draw, the `decisions.md` entry records the seed.

## Checkpoints

The times are 7:00 pm Eastern. The submission is the last commit on `main` before then.

- Proposal, 28 October. `PROPOSAL.md`, at most one page, with the three headings already in that file. The first entry in `decisions.md` records that choice and the alternative you set aside.
- Preliminary results, 18 November. `analysis.ipynb` has the raw-data plot, the summary table, the split, one baseline, one model, and both held-out scores in the units of the decision. `decisions.md` has an entry for the split, the model, and the loss.
- Final presentation, 9 December. `SLIDE.md` is the presentation. `decisions.md` runs from the proposal to the action on that slide. The repository meets `CHECKLIST.md`. The talk is that night, 7:30 to 10:15 pm. Three minutes, one slide, the same length for one person and for a group.

A late commit still gets a comment, and the issue says it was late. The checkpoints have no separate points. If the repository is not in when you are scheduled to present, that slot waits.

## The talk

Four parts on the one slide: the action, the reason, the risk with a number, and what it is worth to be less wrong. The number is the held-out score on `main`. The code and the plots stay in the repository.

## Data

Leave the data files out of git. Attach them to a GitHub release tagged `data`. `data/README.md` names the source and the file names on that release. The notebook reads a local copy of those files from `data/`.

## Tools

R or Python. Use the language you can explain. AI assistants are allowed. On your fork, add one line to this README: what you used, and for what. You are responsible for everything on `main`, including the parts you did not write.

## Files

- `PROPOSAL.md` and `SLIDE.md`. The proposal and the presentation. Replace the prompts. Leave the headings.
- `decisions.md`. Append one entry per choice. Do not rewrite an old entry.
- `CHECKLIST.md`. The lab, as checkboxes. Tick them in the final commit.
- `analysis.ipynb`. The code. A `.py` or `.R` file holds a function two people would otherwise edit in the notebook.
- `requirements.txt` or `renv.lock`. The packages, with versions.
- `fig/`. Plots saved from the notebook.
- `data/README.md`. The source, and the file names on the `data` release.
