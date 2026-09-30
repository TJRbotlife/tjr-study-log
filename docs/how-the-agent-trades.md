# How the agent trades

The agent is flat until a playbook rule clears the bar below. Lesson titles tell us which class is allowed to fill each slot. They do not fill the slot. Day 1 did not teach an entry.

A trade needs every slot. One empty slot means no order.

| Slot | What has to be true | Lessons that may fill it | Filled |
| --- | --- | --- | --- |
| Bias | Higher-timeframe direction for the session | Day 4 Trends, Days 34–36 Daily Bias, Boot Camp 2.0 Day 5 | No |
| Location | Where price has to be before an entry is even considered | Day 6 Break of Structure, Days 8/10/12 Liquidity, Days 14/16/18 Fair value gaps, Days 20/22/24 Order blocks, Days 26/28 Equilibrium | No |
| Trigger | The event that turns a location into an order | Days 30/32/33 Execution, Boot Camp 2.0 Day 5.5 | No |
| Invalidation | The price that proves the idea wrong, written before entry | Day 38 Stop losses, Boot Camp 2.0 Day 6 | No |
| Size | How much is lost if invalidation hits | Day 13 Risk, Day 39 Lot size, Boot Camp 2.0 Days 3, 7, and 9 | No |
| Exit | Where the position comes off if it works | Day 37 Taking profits, Boot Camp 2.0 Day 11 | No |
| Stand down | A reason to do nothing | Day 11 Taking a loss, Day 17 Patience, Day 25 Overconfidence, Day 27 Fear, Day 44 Try not to trade, Day 45 Overcomplicating, Boot Camp 2.0 Days 2 and 12 | Day 1 only: no setup, so stand down |

## The session

1. Read the playbook. If bias, location, trigger, invalidation, or size has no cited rule, the session is flat and the journal says why.
2. If a stand-down rule is active, the session is flat.
3. If every slot is filled, the order is the rule, not a new idea. The note ids are copied into the journal before the click.
4. The stop is the invalidation from the rule. It is not moved farther away.
5. Size comes from the size rule and from `journal/live/STAKE.md` once that file exists. A win does not raise the size inside the same test.
6. The same day, the journal records the rule id, the prices, and the result.

## Paper, then money

Twenty paper sessions come first. They use this same checklist and no broker. The paper result is published even if it loses.

Live money is the operator's, and only after that paper result is in the repo. The amount, the daily max loss, and the test max loss are frozen in `journal/live/STAKE.md` before the first live order. The test is 30 closed trades or the max loss, as written in `docs/experiment.md`.

Until those slots say Yes, the agent does not trade.
