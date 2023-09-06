# scorecard-check-repo-rules-e2e

This repo is configured with repo rule settings that are used as part of [scorecard](https://github.com/ossf/scorecard)'s `Branch-Protection` e2e tests.

The test assumes the following rules are enabled for the `main` branch:
- no force push
- no deletion
- no bypass actors
- dismiss stale reviews (no required review count though)
