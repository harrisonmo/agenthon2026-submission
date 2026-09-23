# Agenthon 2026 submission

Current release: `ghcr.io/harrisonmo/agenthon2026-submission:v0.29.5`

Immutable reference: `ghcr.io/harrisonmo/agenthon2026-submission@sha256:f7cf827531fb15440abf09d2463e358046a4084acff2b15a3d6dfe40059f5fc6`

Submitted as **940283**, 2026-09-22 22:00 GMT-4. Observed **Submitting**; score pending.

Apache-2.0 agent, Python 3.13, Polars 1.39.3, linux/amd64, interface 2.0. Retains v0.29.4 solver, output handling and server-default thinking. Removes the withdrawn default cumulative input-token cap while preserving 25 requests and 4000 output tokens per request. No experimental v0.30-v0.32 solver changes.

87 tests, synthetic HTTP/proxy fixtures, resource-constrained public-unit action replay followed by official smoke, full-layer audit, and anonymous digest pull passed. These are interface/replay checks, not proof of House-model performance or resolution of the prior platform failure. Docker may reuse cached layers during anonymous pull verification.

## Prior submissions

| Version | Submission | Observed status | Score |
|---|---|---|---|
| v0.29.4 | 938770 | Failed | unavailable |
| v0.28.2 | 935884 | Finished | 0.0575 |
| v0.28.1 | 932710 | Failed | 0.1954 |

v0.29.4 digest: `sha256:6c8622ad43f2b0c87ebe40f0b3d0e776e532047d05f1634c30bab1317e1e5eb1`.
v0.28.2 digest: `sha256:a0a25005ad8e57df79232970cece43e5917b61e4a567d0be733d99acccfaf54f`.
v0.28.1 digest: `sha256:c2684c46c3a28d4551935969212c028d36e9102ed0e42454e8b5ceb001b823ea`.

This public repository contains release metadata and license only. No team key, signed team proof, evaluation dataset or experiment trajectories are included. Container images expose their bundled agent source and dependencies; third-party dependencies retain their own licenses.

[Competition submissions](https://www.codabench.org/competitions/17765/#/participate-tab)
