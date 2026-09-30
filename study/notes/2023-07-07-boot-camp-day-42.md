# Boot Camp Day 42: How to Backtest

- Source: [Boot Camp Day 42: How to Backtest](https://www.youtube.com/watch?v=NPG_BZ_83fo)
- Channel: TJR (`UCGHBUXjDCeiIXNdKR0HUZnA`)
- Published: 2023-07-07
- Lane: boot-camp, order 42 of 46
- Video id: `NPG_BZ_83fo`

## What we learned

Day 42 answers a request for a backtest method, and he says he will describe what he actually uses. Viewer requests had centered on bar replay. He does not treat that tool as the best practice. His review is to scroll a finished chart to some earlier day and read it from the higher time frames down, looking for the building blocks already taught: liquidity sweep, break of structure, order block, fair value gap.

The objection to replay is information the live session would not have had. On a fifteen-minute replay, shifting up to the daily, the four-hour, or the hourly shows the whole higher-time-frame candle, including the part that had not printed at the replay moment. Dropping back to the fifteen-minute returns to the earlier price. He says that breaks the daily bias, which he treats as required before any low-time-frame decision. Stay on the lower chart long enough and an hourly break of structure can flip the idea while the eye is still hunting the old direction. He expects that kind of replay to score worse than the same person in a live market, so he judges ability from live bars.

He also says replay skips the part of a candle that creates pressure. A live candle wicks up and down while it forms. Replay steps from finished bar to finished bar. For a weekend, when the live session is closed, his drill is the prior week: pick a pair, find one or two trades that would have fit, and mark the building blocks through those days until spotting them is fast. He points that drill back at the earlier homework on sweeps, breaks, gaps, and order blocks. Once those are easy to see, he says what is left is the headspace of a live session. If the results are still poor after that, the work returns to the small repeated mistakes, which this video says it is not yet covering in detail.

## How we learned it

Public captions, paraphrased. The video stays on YouTube.

- `00:01:16` He says bar replay is not the best backtest in his view. He wants a full chart scrolled back to a chosen day and read from the top down.
- `00:02:19` On a fifteen-minute replay, the daily, four-hour, and hourly charts show the completed candle, while the fifteen-minute still sits at the earlier price. That is the flaw he names.
- `00:03:02` He calls the live market the real test of a method. The chart review is for spotting the same building blocks without pretending the session is live.
- `00:04:15` He says a low-time-frame entry has nowhere honest to stand if the daily and higher-time-frame bias are unknown.
- `00:05:17` He sends the drill back to the earlier lessons: mark order blocks, fair value gaps, liquidity sweeps, and breaks of structure over and over.
- `00:06:15` If the replay stays on the fifteen-minute, an hourly break of structure can reverse a bearish idea while the review is still hunting shorts.
- `00:06:56` He contrasts a forming candle, which moves and creates emotion, with replay's finished bars stepping one after another.
- `00:08:00` Over a weekend he wants the previous week reviewed, one or two fitting trades on a pair, and the building blocks marked through those days.
- `00:08:50` Once those spots are automatic, he says the missing piece in live markets is psychology.
- `00:09:01` If the results are still off after the spotting is learned, he says the next work is chipping at the small mistakes.

## What to remember

- His preferred review is a finished chart read from the higher time frames down, not a single-time-frame replay.
- Replay can reveal the rest of a higher-time-frame candle that was still forming at the moment being studied, so the bias in that exercise is contaminated.
- He judges the method on live bars, because that is where a candle's wicks and the feeling of being in the trade both exist.
- The offline version he describes is repetition of sweeps, breaks, gaps, and order blocks on a recent week, until the spots are fast.
- After the spots are easy, this lesson says the remaining work is psychology, and then the small repeated mistakes.
