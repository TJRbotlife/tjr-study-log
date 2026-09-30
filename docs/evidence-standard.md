# Evidence standard

Anyone checking this notebook should be able to walk from a note back to a public video.

## What counts

- A catalog row in `catalog/queue.json` with the YouTube id.
- A study note that says what was learned, cites a timestamp, and says what to remember, in our own words.
- A ledger row in `ledger/log.jsonl` for every note.

## What does not count

- A thumbnail, a title, or a memory of the video.
- A caption file or a copied transcript. Those are not committed.

## Note shape

```text
# Title
Source, date, lane, video id.

## What we learned
Short claims in our words.

## How we learned it
Timestamp and what was said or shown.

## What to remember
The point to carry into the next lesson.
```
