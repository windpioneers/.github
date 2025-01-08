# WindPioneers GitHub Settings

Welcome to WindPioneers! This repository defines settings and workflows that are applied universally across all
WindPioneers repositories.

## Conventions

Some general rules that we stick to when using GitHub

### Repository naming
- Repositories are named using `kebab-case` conventions to reduce friction when collaborating with others or setting up build scripts
- Repositories should have meaningful names with a subject/area, as well as an indicator of function/purpose, eg `wake-service` is a webservice (function/purpose) to calculate wake interactions (the subject/area), `windquest-frontend` is part of the windquest group of apps.

### Best practices
- It's your responsibility to keep devcontainers, dev tooling and CI/CD workflows up to date for your repositories. You can see (and add to yourself) some best practices on [python libraries and applications](https://github.com/orgs/octue/discussions/categories/python-libraries-and-applications), [semantic versioning](https://github.com/orgs/octue/discussions/categories/semantic-versioning) and [Terraform / IAC](https://github.com/orgs/octue/discussions/categories/terraform-infrastructure-as-code).

### Code style rules 
- All repos should use `pre-commit` to enforce styling consistency and QC. See established repos for pre-comit configuration examples specific to your language.
- Frontend / Javascript repositories should use [`biome`](https://biomejs.dev/) as a comprehensive code formatter
- Python repositories should conform to the [`ruff` style guide](https://docs.astral.sh/ruff/)
- R repositories should conform to the [`google R` style guide](https://google.github.io/styleguide/Rguide.html)
- C++ repositories should conform to the [`google C++` style guide](https://google.github.io/styleguide/cppguide.html)
