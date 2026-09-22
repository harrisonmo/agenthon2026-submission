# Agenthon 2026 submission

Current published candidate: `ghcr.io/harrisonmo/agenthon2026-submission:v0.29.4` (submitted to Codabench as **938770** on 2026-09-22; observed **Submitting**, score pending).

Immutable reference: `ghcr.io/harrisonmo/agenthon2026-submission@sha256:6c8622ad43f2b0c87ebe40f0b3d0e776e532047d05f1634c30bab1317e1e5eb1`

Apache-2.0 agent; Python 3.13, Polars 1.39.3, interface 2.0, linux/amd64. Official HTTP backend only. This release retains server-default thinking and adds public output-requirement validation. No Terra CLI bridge, team key, evaluation dataset or experiment trajectories are bundled.

Release source and image-layer audit completed. Anonymous registry pull and image identity verified. Synthetic interface tests passed; House-model behavior remains unverified. Third-party dependencies retain their licenses. Container images expose their bundled source and dependencies.

# Prior submissions

Submitted release: `ghcr.io/harrisonmo/agenthon2026-submission:v0.28.2`

Immutable digest: `sha256:a0a25005ad8e57df79232970cece43e5917b61e4a567d0be733d99acccfaf54f`. Anonymous pull and image identity verified. Submitted on 2026-09-20 as **935884**; last observed status **Submitting**, score pending.

This stability release explicitly disables model thinking, excludes directory mentions from required files, and preserves structurally complete outputs when a known budget/deadline limit is reached. Missing-output failures remain failures. Final-image validation: 50 regression tests, one proxy/CLI fixture and 11 synthetic protocol scenarios. Real House-model effectiveness remains to be measured.

Previous official release v0.28.1, submission **932710**, showed score **0.1954** and 17 scored tasks out of 87 in the run summary. The status UI previously remained Running. Previous digest: `sha256:c2684c46c3a28d4551935969212c028d36e9102ed0e42454e8b5ceb001b823ea`.

Participant agent code is Apache-2.0. Third-party dependencies retain their licenses. This repository contains release metadata only; no private experiment data, credentials or team proof. Container images expose their bundled agent source and dependencies.

[Competition submissions](https://www.codabench.org/competitions/17765/#/participate-tab)
