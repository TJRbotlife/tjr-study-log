# Evidence standard

Anyone checking this agent should be able to walk from a trade back to a sentence in a public video.

## What counts

- A catalog row in `catalog/queue.json` with the YouTube id.
- A study note that paraphrases one claim and cites a timestamp.
- A ledger row in `ledger/log.jsonl` for every note or rule change.
- A playbook rule that lists the note ids it depends on.
- A journal file for any paper or live result.

## What does not count

- A thumbnail, a title, or a memory of the video.
- A caption file or a copied transcript. Those are not committed.
- A rule with no note id.
- A win, a loss, or a profit number with no file under `journal/`.
- Homework that is about motivation, unless the note says the use is process-only.

## Note shape

```text
# Title
Source, date, lane, video id.

## What we learned
Short claims in our words.

## How we learned it
Timestamp and what was said or shown.

## How we will use it
playbook section, or process-only, or wait-for-later-day.
```

## Before any public trading claim

`STATUS.md` has to show paper sessions, and each claimed decision has to name a rule id plus a journal path. Until then the public statement is: the agent is still studying.
