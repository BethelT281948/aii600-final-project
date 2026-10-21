# Checklist

The final commit on `main` ticks every line you have done. A line you cannot tick needs one sentence saying why.

## 1. Question

- [ ] The question is one sentence, then one quantity with units and a time window.
- [ ] The decision is named, and the loss or profit is a formula. The costlier mistake is named.
- [ ] A layer diagram: data, model, prediction, decision.

## 2. Data

- [ ] Source, unit of observation, sample size, time span, and how it was collected.
- [ ] How the measurement differs from the quantity the decision needs, and whether that gap is bias or noise.
- [ ] One plot of the raw data and one table of summary statistics, before any model.

## 3. Model

- [ ] The model as equations. Each parameter in words, and the mechanism it stands for.
- [ ] The assumptions, and the one you trust least.
- [ ] Simulated data from the model, checked against the real data. If the fit can recover known parameters, show that it does.

## 4. Uncertainty

- [ ] Every prediction carries a standard error, an interval, or a predictive distribution.
- [ ] The error is measured out of sample, and you say how it grows as the forecast moves further from the data.
- [ ] Residuals plotted against time or against the prediction, and a statement of whether the error looks like noise or like bias.

## 5. Decision

- [ ] An explicit rule from the prediction to the action, and why the loss picks that rule.
- [ ] How the action changes when the main inputs change.
- [ ] What a better model or more data would be worth, in the units of the loss.

## 6. Evaluation

- [ ] A held-out set the model never saw, and a calibration check.
- [ ] The method scored against a simple baseline in the units of the decision, not only RMSE or R².
- [ ] Where the method wins, and where it ties.

## Decisions

- [ ] `decisions.md` is the history: each choice, why, the alternative rejected, and what would change it. Old entries are still in the file.

## 7. Communicate

- [ ] `SLIDE.md` states the action, the reason, the risk with a number, and the value of being less wrong.
- [ ] The key effects are in plain language and in real units.
- [ ] The limits: where the model should not be trusted, what was assumed, and what you would do with more time or data.

## Repository

- [ ] Names and GitHub usernames are in `README.md`.
- [ ] A group reached `main` through pull requests, and each request names a `decisions.md` entry.
- [ ] `requirements.txt` or `renv.lock` pins the packages the notebook imports.
- [ ] The `data` release holds the data files. The notebook on `main` was run from the top and committed with its outputs. Secrets and fitted weights are not in git.

## Disclosure

- [ ] One line in `README.md`: which AI tools you used, and for what.
