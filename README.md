# Bet Diary

**Your private Stake record.**

A one-page tracker for your Stake rounds: log each slip and see your real
record — win rate, profit/loss by sport and by odds range — instead of
remembering the wins and forgetting the losses.

## What it does

- **Scoreboard** — total staked, returned, profit/loss, win rate, ROI and
  pending bets, computed from settled bets only.
- **Where the money goes** — profit/loss split by sport and by odds band
  (short under 1.30 / mid 1.30–1.99 / long 2.00+), so you can see whether
  the short-odds grind or the bolder play actually pays.
- **Log a bet** — date, sport, pick, odds, stake, result (won / lost /
  refunded / pending), round label and note. A win's return is worked out
  from stake × odds, or from an amount you type in.
- **Every slip** — filter by result, sport or search text; delete any row.
- **Your data** — export/import JSON, restore the seeded history, or clear
  everything. Data lives only in the browser (localStorage). No account,
  no upload, nothing shared.

## Seeded history

Pre-loaded with your real Nov 6–10 rounds on the belugallary account, as
recorded in chat: Round 1 (7 Nov, 5 × ₦50, +₦9.50), Round 2 (8 Nov,
5 × ₦50, +₦38.00), the first ₦10 spread (8 Nov, 12 bets, +₦20.40), the
Juventus live bet (−₦50), the self-placed 35-leg multi (−₦7), the Mines
session (+₦1.25), Spread 2 (9 Nov, 23 × ₦10, −₦73.20), Mini-spread 1
(+₦0.50) and Mini-spread 2 (−₦25.00). 56 entries: ₦1,087 staked,
₦1,001.45 returned, net −₦85.55; 33 won, 22 lost, 1 refunded.

Results come from public match reports and Stake checks at the time; the
final balances were expected figures, not all Stake-confirmed, and your
own Mines play after 9 Nov is not included. A refund counts as its stake
returned.

## Honesty notes

- Nothing here is a tip and no pick is a guaranteed win — the diary just
  shows what actually happened.
- The seeded figures are only as good as the records they came from; if a
  result looks wrong, delete the row and re-add it.

## Tech

One static page (`site/index.html`) plus a banner drawn with Python/PIL.
No build step. Published via GitHub Pages from the `site/` folder.
