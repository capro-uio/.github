# Contributing to CAPRO projects

Thanks for taking the time. These are the defaults across the
[CAPRO organisation](https://github.com/capro-uio); a repository with its own
`CONTRIBUTING.md` overrides them.

## Before you start

- For anything more than a typo, open an issue first so we can agree on the
  approach before you spend time on it.
- Check whether the repository has a `README` section on development setup —
  most of our R packages are developed with
  [devtools](https://devtools.r-lib.org/) and [renv](https://rstudio.github.io/renv/).

## Pull requests

- Branch off `main` and open the pull request against `main`.
- Keep each pull request to one logical change. Several small ones are easier
  to review than one large one.
- Describe what the change does and why. Link the issue it closes.
- New behaviour comes with tests in the same pull request.
- Make sure CI is green before asking for review.

## R packages

- Follow the [tidyverse style guide](https://style.tidyverse.org/).
- Document exported functions with [roxygen2](https://roxygen2.r-lib.org/) and
  run `devtools::document()` before committing.
- Tests use [testthat](https://testthat.r-lib.org/) 3rd edition.
- Add a bullet to `NEWS.md` for anything a user would notice.
- `devtools::check()` should pass with no errors, warnings or notes.

## Reporting bugs

Open an issue with a minimal reproducible example — the smallest piece of code
and data that shows the problem — along with the output of `sessionInfo()` for R
projects, or your browser and version for web projects.

## Code of conduct

Participation in these projects is governed by the
[CAPRO code of conduct](CODE_OF_CONDUCT.md).
