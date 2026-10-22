# GitHub Open-Source Activity Report — HeziLiu

Snapshot compiled from live GitHub API data. No estimates; every value below is taken directly from an API response. (Publishing note: this report is served as a single file, `activity-report.md`, because the gist API is blocked for the current token — see §7 note.)

## 1. Account basics

- **Login:** HeziLiu
- **Display name:** Hezi Liu
- **Profile:** https://github.com/HeziLiu
- Account created: 2017-05-22T10:11:01Z
- Public repositories: 4 · Public gists: 0 · Followers: 5 · Following: 5

## 2. Repository inventory (forks included)

| Repository | Type | Description | Primary language | Last push (UTC) |
|---|---|---|---|---|
| [Little-rookie](https://github.com/HeziLiu/Little-rookie) | Original | Undergraduate coursework | Java | 2019-06-02T07:47:15Z |
| [Big-Buzzard](https://github.com/HeziLiu/Big-Buzzard) | Original | For future.... | none detected | 2018-05-17T10:23:01Z |
| [CodingInterviewChinese2](https://github.com/HeziLiu/CodingInterviewChinese2) | Fork | 《剑指Offer》第二版源代码 | C++ | 2018-12-28T04:40:02Z |
| [awesome-chatgpt-prompts-zh](https://github.com/HeziLiu/awesome-chatgpt-prompts-zh) | Fork | ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。 | none detected | 2023-04-13T08:42:43Z |

## 3. Most recent commit per repository

| Repository | Short SHA | First line of message | Committed at (UTC) | Author login |
|---|---|---|---|---|
| Little-rookie | `964bd6b` | DELETE | 2019-06-02T07:47:10Z | HeziLiu |
| Big-Buzzard | `4ce5a6d` | Merge branch 'master' of https://github.com/Tackic/Big-Buzzard | 2018-05-17T10:22:21Z | HeziLiu |
| CodingInterviewChinese2 | `2d6eb6d` | Minor changes on license comments | 2016-12-07T05:25:09Z | zhedahht (upstream) |
| awesome-chatgpt-prompts-zh | `2d1ff55` | Merge pull request #127 from layyback/main | 2023-04-13T07:30:55Z | PlexPt (upstream) |

All four repositories contain commits; none are empty. In the two forks the most recent commits were authored upstream, not by HeziLiu.

## 4. Pull requests

**Open PRs in my own repositories (HeziLiu/Little-rookie, Big-Buzzard, CodingInterviewChinese2, awesome-chatgpt-prompts-zh):** none — the open-PR list returned empty for all four repositories.

**Open PRs authored elsewhere:** 902 open pull requests authored by HeziLiu across GitHub (search: `author:HeziLiu is:open`), all of them inside the `mcpmark-eval-liuhezi` organization. Notable examples (by most recent update):

| PR | Repository | Title | Updated (UTC) |
|---|---|---|---|
| [#1](https://github.com/mcpmark-eval-liuhezi/aco-101-labs/pull/1) | mcpmark-eval-liuhezi/aco-101-labs | Add course lab materials | 2026-10-22T11:22:15Z |
| [#13](https://github.com/mcpmark-eval-liuhezi/release-readiness-audit/pull/13) | mcpmark-eval-liuhezi/release-readiness-audit | Add release readiness checklist | 2026-10-22T11:12:37Z |
| [#1](https://github.com/mcpmark-eval-liuhezi/release-readiness-audit-loop-proveout/pull/1) | mcpmark-eval-liuhezi/release-readiness-audit-loop-proveout | Add audit follow-up notes | 2026-10-22T11:09:18Z |
| [#1](https://github.com/mcpmark-eval-liuhezi/security-briefings/pull/1) | mcpmark-eval-liuhezi/security-briefings | Add incident briefings: Log4Shell and Spring4Shell | 2026-10-22T11:06:51Z |
| [#2](https://github.com/mcpmark-eval-liuhezi/release-security-audit/pull/2) | mcpmark-eval-liuhezi/release-security-audit | Release & security audit report | 2026-10-22T11:03:14Z |

### Most recently updated open PR — diff details

[PR #1 "Add course lab materials"](https://github.com/mcpmark-eval-liuhezi/aco-101-labs/pull/1) in mcpmark-eval-liuhezi/aco-101-labs (branch `course-materials`, created & updated 2026-10-22T11:22:15Z):

- **Files touched:** 1
- **Total additions:** 11
- **Total deletions:** 0
- **Most-changed file:** `labs/README.md` — 11 additions, 0 deletions, status `added`. It lists Lab 0 – Environment Setup (10 points) and Lab 1 – Deploying to Kubernetes (20 points) for the Applied Cloud Operations (ACO-101) cohort.

## 5. CI (GitHub Actions)

None of my four repositories use GitHub Actions — the workflow list returned zero workflows for Little-rookie, Big-Buzzard, CodingInterviewChinese2 and awesome-chatgpt-prompts-zh. Consequently there are no workflow runs, statuses, conclusions, artifacts, or logs to report.

## 6. Numbers

All calculations run through a calculator:

- **Commits retrieved per repository:** Little-rookie 90 · Big-Buzzard 4 · CodingInterviewChinese2 100 · awesome-chatgpt-prompts-zh 141
- **Average commits per repository:** (90 + 4 + 100 + 141) = 335 retrieved commits; 335 / 4 = **83.75 commits per repository**
- **Total churn of the most recently updated open PR (#1, aco-101-labs):** additions + deletions = 11 + 0 = **11 lines**
- **Artifact sizes in MiB:** not applicable — no repositories use GitHub Actions, so no artifacts exist to convert.

## 7. Publishing note

The report was requested as a gist; the gist API returned `403 Resource not accessible by personal access token` for the authenticated token, so no gist could be created. It is published instead as a single-file report (`activity-report.md`) in the `github-activity-audit` repository, at a stable, forwardable link: https://github.com/mcpmark-eval-liuhezi/github-activity-audit/blob/main/activity-report.md