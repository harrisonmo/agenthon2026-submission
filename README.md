# Agenthon 2026 submission

Current release: `ghcr.io/harrisonmo/agenthon2026-submission:v0.32.1`

Immutable reference: `ghcr.io/harrisonmo/agenthon2026-submission@sha256:43c18220558ffd17917c9202ebcc13e7f99995ae2fd2eaf56ba36e194e082efc`

Submitted as **945644**, 2026-09-25 22:12 GMT-4. Observed **Submitting**; score pending.

Apache-2.0, Python 3.13, Polars 1.39.3, linux/amd64, interface2.0. v0.29.6 official runtime plus public JSON template checks and one structural repair review when budget permits. Advisory false/error values alone do not trigger review. Same server-default thinking, 25 requests and 4000 output tokens/request.

112 tests, HTTP/proxy fixtures, constrained public-unit replay and official smoke, full-layer audit and anonymous digest pull passed. All 15 previously correct artifacts retained in 32-artifact replay. No new local live model solves; House accuracy remains unproven. Anonymous pulls may reuse local layers.

## Prior submissions

| Version | Submission | Observed status | Score |
|---|---|---|---|
| v0.29.6 | 943024 | Finished | 0.1977 (17/86) |
| v0.29.5 | 940283 | Finished | 0.1744 (15/86) |
| v0.29.4 | 938770 | Failed | unavailable |
| v0.28.2 | 935884 | Finished | 0.0575 |
| v0.28.1 | 932710 | Failed | 0.1954 |

v0.29.4 digest: `sha256:6c8622ad43f2b0c87ebe40f0b3d0e776e532047d05f1634c30bab1317e1e5eb1`.
v0.28.2 digest: `sha256:a0a25005ad8e57df79232970cece43e5917b61e4a567d0be733d99acccfaf54f`.
v0.28.1 digest: `sha256:c2684c46c3a28d4551935969212c028d36e9102ed0e42454e8b5ceb001b823ea`.

This public repository contains release metadata and license only. No team key, signed team proof, evaluation dataset or experiment trajectories are included. Container images expose their bundled agent source and dependencies; third-party dependencies retain their own licenses.

[Competition submissions](https://www.codabench.org/competitions/17765/#/participate-tab)
