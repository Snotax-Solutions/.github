# Contributing

Thank you for helping with Snotax. These rules apply to every repository of the Snotax Solutions organization unless the
repository has its own `CONTRIBUTING.md`.

1. **Branch from `main`** and keep each pull request focused on one change.
2. **Open a pull request** into `main`. Fill in the template: what changed, why, and how it was tested.
3. **CI must be green** before merging. Add the `build` label to run the full pipeline (container images) where the
   repository supports it.
4. **Merge with "Squash and merge"**; the pull request title becomes the commit message, so make it descriptive.
5. **Never commit secrets.** Secrets live encrypted (SOPS) or in the CI secret store; CI runs a secret scan.
6. Report security issues privately — see [SECURITY.md](SECURITY.md).
