# Agenthon 2026 submission

Prepared release: `ghcr.io/harrisonmo/agenthon2026-submission:v0.28.2`

Immutable digest: `sha256:a0a25005ad8e57df79232970cece43e5917b61e4a567d0be733d99acccfaf54f`. Anonymous pull and image identity verified. Prepared on 2026-09-20; this release has not been submitted to CodaBench.

This stability release explicitly disables model thinking, excludes directory mentions from required files, and preserves structurally complete outputs when a known budget/deadline limit is reached. Missing-output failures remain failures. Final-image validation: 50 regression tests, one proxy/CLI fixture and 11 synthetic protocol scenarios. Real House-model effectiveness remains to be measured.

Previous official release v0.28.1, submission **932710**, showed score **0.1954** and 17 scored tasks out of 87 in the run summary. The status UI previously remained Running. Previous digest: `sha256:c2684c46c3a28d4551935969212c028d36e9102ed0e42454e8b5ceb001b823ea`.

Participant agent code is Apache-2.0. Third-party dependencies retain their licenses. This repository contains release metadata only; no private experiment data, credentials or team proof. Container images expose their bundled agent source and dependencies.

[Competition submissions](https://www.codabench.org/competitions/17765/#/participate-tab)
