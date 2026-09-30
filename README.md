# TJR boot camp study log

Public notebook for an agent that is studying [TJR](https://www.youtube.com/@TJR)'s free YouTube boot camps, then trading the rules those lessons actually state. The test is whether that student becomes profitable. This repository is not affiliated with TJR, and it is not his course.

The score is [STATUS.md](STATUS.md). Right now: one lesson noted, no playbook rules, no paper trades, no live trades. The pass/fail contract is [docs/experiment.md](docs/experiment.md). How the folders connect is [docs/how-it-works.md](docs/how-it-works.md). When an order is allowed is [docs/how-the-agent-trades.md](docs/how-the-agent-trades.md).

## What is stored

Original study notes with a video link and a timestamp. Playlist metadata for the two public boot camps. An append-only ledger of what changed.

Video files, captions, and transcripts are not stored. The paid Blueprint is out of scope. Lifestyle and promo uploads are not in this queue.

## Study order

1. [Boot Camp](https://www.youtube.com/playlist?list=PLDVXJ0hsxGL_K5M9jTLb2V_cLbWTz4ITR) — 46 lessons, Day 1 through Day 46.
2. [Boot Camp 2.0](https://www.youtube.com/playlist?list=PLKE_22Jx497u8rJX1n6Yq20ROA_A2HrWt) — 14 lessons.

The full index is [catalog/INDEX.md](catalog/INDEX.md). Machine-readable queue: [catalog/queue.json](catalog/queue.json).

## How a lesson becomes a trading rule

A note has to answer three questions: what was learned, how it was learned, and how the agent would use it. Psychology days are marked process-only. A playbook rule needs a merged note id, an entry, an invalidation, and a stand-down. Rules are not written from the first video.

See [docs/evidence-standard.md](docs/evidence-standard.md).

## Trading

The agent is flat. Live money comes only after every lesson is noted, the playbook cites those notes, and 20 paper sessions are published. The stake is the operator's own capital, with a max loss written down before the first order. Day trading loses money for most people. Nothing here is a signal or financial advice.
