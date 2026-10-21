# Open-Source Hygiene Review 2026 — Survey Findings

Account surveyed: **HeziLiu** (https://github.com/HeziLiu)
Date of survey: 2026-10-21

## 1. Starred Repositories Survey

The starred list is **not empty** — 6 repositories were found:

| # | Repository | Language | Stars | One-line note |
|---|------------|----------|-------|---------------|
| 1 | [OpenBMB/AgentCPM](https://github.com/OpenBMB/AgentCPM) | Python | 833 | End-to-end infrastructure for training and evaluating various LLM agents |
| 2 | [PaddlePaddle/ERNIE](https://github.com/PaddlePaddle/ERNIE) | Python | 7,739 | Official repository for ERNIE 4.5 and ERNIEKit, industrial-grade toolkit based on PaddlePaddle |
| 3 | [FudanNLP/fastNLP](https://github.com/FudanNLP/fastNLP) | Python | 3,138 | Modularized and extensible NLP framework (currently in incubation) |
| 4 | [maplezzz/NTU_ML2017_Hung-yi-Lee_HW](https://github.com/maplezzz/NTU_ML2017_Hung-yi-Lee_HW) | Jupyter Notebook | 873 | NTU ML2017 course homework by Hung-yi Lee |
| 5 | [fighting41love/funNLP](https://github.com/fighting41love/funNLP) | Python | 84,065 | Large curated collection of Chinese/English NLP corpora, datasets, tools, and lexicons |
| 6 | [996icu/996.ICU](https://github.com/996icu/996.ICU) | — | 277,148 | "Repo for counting stars and contributing. Press F to pay respect to glorious developers." |

Observations:
- All 6 starred repositories are public, non-fork, non-archived, and recently updated.
- The list skews heavily toward NLP / machine learning (Python and Jupyter Notebook).
- Follow-up tracked in issue #2: [Summarize starred repositories](https://github.com/mcpmark-eval-liuhezi/oss-hygiene-2026/issues/2)

## 2. Organization Security Advisory Check

Organizations identified from team memberships: **`mcpmark-eval-liuhezi`**

Check result: the check **could not be completed**. The API call returned a permission error:

```
GET https://api.github.com/orgs/mcpmark-eval-liuhezi/security-advisories?state=published
403 Resource not accessible by personal access token
```

The personal access token used for this survey does not have permission to read organization-level security advisories, so it could not be determined whether the organization has any published repository security advisories (present or absent). This check should be re-run with a token that has organization security-advisory read permissions before any conclusion is drawn.

Follow-up tracked in issue #3: [Audit organization security advisories](https://github.com/mcpmark-eval-liuhezi/oss-hygiene-2026/issues/3)

## 3. Tracker Issue List

| Issue | Title | Status |
|-------|-------|--------|
| [#1](https://github.com/mcpmark-eval-liuhezi/oss-hygiene-2026/issues/1) | Open-source hygiene review 2026 | Parent issue — open |
| [#2](https://github.com/mcpmark-eval-liuhezi/oss-hygiene-2026/issues/2) | Summarize starred repositories | Sub-issue of #1 — open |
| [#3](https://github.com/mcpmark-eval-liuhezi/oss-hygiene-2026/issues/3) | Audit organization security advisories | Sub-issue of #1 — open |

Both sub-issues #2 and #3 were verified to be attached to parent issue #1.
