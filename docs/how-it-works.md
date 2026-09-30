# How the pieces fit

The agent is a student with a public notebook. Each box below is a folder in this repo. Nothing skips ahead.

```text
boot camp videos
    -> catalog/queue.json          what to study, in order
    -> study/notes/                what the lesson said, in our words, with timestamps
    -> ledger/log.jsonl            when that note or rule entered the record
    -> playbook/rules/             if-then rules that cite note ids
    -> journal/paper/              20 sessions with no money
    -> journal/live/               real orders, only after the paper result is published
    -> STATUS.md                   the score anyone can check
```

## Study

`docs/agent-study.md` is the assignment. The next run takes the first `queued` video, writes one note, and stops. Captions are read to write the note. Caption files are not committed.

A note answers three questions: what we learned, how we learned it, and how a trade would use it. Use tags are `process-only`, `hypothesis`, or `rule-candidate`. Day 1 is process-only. It does not unlock a trade.

## Playbook

The synthesize step runs after Boot Camp is fully noted, then again after Boot Camp 2.0. It may propose a rule. It may not invent one. If two days disagree, both timestamps go in `playbook/conflicts.md` and the rule stays untradable until one lesson clearly replaces the other.

## Journal

Paper sessions prove the agent obeys the playbook. Live sessions test whether those rules make money. Both use the same fields: rule id, note id, decision, result. `docs/experiment.md` is the pass/fail contract.

## What is still empty

Lessons noted: 1 of 60. Rules: 0. Paper sessions: 0. Live trades: 0. The agent is flat.
