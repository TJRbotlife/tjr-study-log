# Study agent

Take the first video in `catalog/queue.json` whose status is `queued`. Finish that one video. Leave the rest queued.

## Do

- Watch or read that public video.
- Write one note under `study/notes/` in the shape from `docs/evidence-standard.md`.
- Set that queue row to `noted` and point `note` at the file.
- Append one JSON line to `ledger/log.jsonl`.
- Update the counts in `STATUS.md` and `catalog/INDEX.md`.
- Open a pull request. Do not merge it yourself.

## Do not

- Commit captions, transcripts, or video files.
- Study Boot Camp 2.0 before Boot Camp is fully noted.
- Add a playbook rule from a process-only day.
- Invent a setup the video did not state.
- Smooth over a disagreement with an earlier note. Write the conflict in `playbook/conflicts.md` and cite both timestamps.
- Place a trade, add an exchange key, or change `journal/` except to record a paper session the operator actually ran.

## Use tags

- `process-only` for mindset, homework, and journaling with no entry rule.
- `hypothesis` for a market claim that a later lesson still has to define.
- `rule-candidate` only when the video states bias, location, trigger, invalidation, and stand-down.
