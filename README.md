# AII 600 final project

Fork this repository once per project. The fork is the project. The three checkpoints are files on `main`.

Follow the [final project lab](https://vsokolov.org/labs/final-project-lab.html) from the question through the decision to the one-slide summary. The strawberry harvest on that page is the worked example. Your project is your own hypothesis, your own data, and a decision someone will make differently because of the model. `CHECKLIST.md` is the lab's "In your project" boxes.

## Who

Alone, or a group of at most three. One person forks. That person adds the other members as collaborators with Write access, and adds `VadimSokolov` with Read access. One person speaks at the presentation. Every member can explain the whole repository.

## Fork

1. Accept the invitation to this repository, then fork it. The fork of a private repository stays private.
2. On the fork, open Settings, then General, then Features, and turn Issues on.
3. Settings, then Collaborators. Add teammates with Write access. Add `VadimSokolov` with Read access.
4. Clone the fork. Do the work on `main` and merge before the deadline. A branch that has not been merged is not submitted.
5. The invitation to `VadimSokolov` expires after seven days. Send it before 28 October.

Feedback comes back as an issue on the fork, labeled `proposal`, `preliminary`, or `final`.

## Checkpoints

The times are 7:00 pm Eastern. The submission is the last commit on `main` before then.

- Proposal, 28 October. `PROPOSAL.md`, at most one page, with the three headings already in that file.
- Preliminary results, 18 November. `PRELIM.md` and `analysis.ipynb`. A plot of the raw data, a summary table, a training split, one baseline, one model, both scored on held-out data in the units of the decision, and the loss as a formula.
- Final presentation, 9 December. The repository meets `CHECKLIST.md`, and `SLIDE.md` is the slide. The talk is that night, 7:30 to 10:15 pm. Three minutes, one slide, the same length for one person and for a group.

A late commit still gets a comment, and the issue says it was late. The checkpoints have no separate points. If the repository is not in when you are scheduled to present, that slot waits.

## The talk

Four parts on the one slide: the action, the reason, the risk with a number, and what it is worth to be less wrong. The number is the held-out score on `main`. The code and the plots stay in the repository.

## Data

Do not commit confidential, restricted, regulated, or identifiable data. Do not upload such data to an external assistant unless the owner has authorized that use. The `data/` folder is gitignored except for `data/README.md`, which names the source and how to obtain the files.

## Tools

R or Python. Use the language you can explain. AI assistants are allowed. On your fork, add one line to this README: what you used, and for what. You are responsible for everything on `main`, including the parts you did not write.

## Files

- `PROPOSAL.md`, `PRELIM.md`, `SLIDE.md`. Replace the prompts. Leave the headings.
- `CHECKLIST.md`. The lab, as checkboxes. Tick them in the final commit.
- `analysis.ipynb`. The analysis.
- `fig/`. Plots saved from the notebook.
- `data/README.md`. Where the data came from, and how to place the files on a local machine.
