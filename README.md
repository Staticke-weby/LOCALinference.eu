# LOCALinference.eu

This repository contains **only the deployment workflow** for the English
edition of LOCALinference. The source lives in
[Staticke-weby/LocalInference.cz](https://github.com/Staticke-weby/LOCALinference.cz),
in `sites/eu/`.

The workflow checks out the public Czech repository, builds `sites/eu`
and deploys the result to GitHub Pages. There is no cross-repo token:
the Czech source is public and this repository only publishes the output.

- Custom domain: `www.localinference.eu`
- Build: hourly and on every push to this repository
- Manual run: Actions → Build EN from CZ source → Run workflow
- Czech edition: https://www.localinference.cz

<!-- build trigger -->
<!-- deploy 2026-11-05T13:52:15.9532943+01:00 -->
<!-- deploy 2026-11-05T13:59:15.0723111+01:00 -->
<!-- deploy 2026-11-05T14:12:17.9221489+01:00 -->
