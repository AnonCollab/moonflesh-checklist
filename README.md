# Moonflesh Checklist — Epoch Operation: Taubound

A shareable checklist for every item Praghasa sells for **Moonflesh** in Warframe's
**Epoch Operation: Taubound** (Oct 15 – Nov 17, 2026).

**Live page:** https://anoncollab.github.io/moonflesh-checklist/

## What it does

- Lists all 50 shop listings with their Moonflesh price and purchase limit
- One-time items: mark **To farm / Bought / Don't plan to farm**
- Arcanes and repeatable packs: track copies bought (stepper / Max), or Skip the rest
- **Plan to buy** per arcane/pack: defaults to the shop max, but you can lower it to
  just what you want — e.g. if you already own 3 copies of an arcane, enter that in
  **Already have** and the page sets your plan to the 18 that top you up to max rank
  (21 total). Totals only count your planned copies.
- Live totals: Moonflesh **spent**, **still to farm**, planned total, and skipped value
- Search and filters, a copyable progress summary, and a two-tap reset

## How progress is saved

Progress is saved in your browser's **localStorage** — automatically, on the same
device and browser you opened the page in. Close the page and come back later and
your checklist is still there. Nothing is uploaded anywhere, and everyone who opens
the link gets their own separate checklist. A different browser/device, private
browsing, or clearing browser data starts you fresh.

**Updates don't wipe progress:** the storage key (`moonflesh-checklist-v1`) and all
item ids never change between versions. New settings (like Plan to buy) are added
with defaults that match the old behaviour, so an existing saved checklist loads
with its progress and totals unchanged until you deliberately change a plan.

## Totals

- 5,950 Moonflesh — all one-time items
- 6,056 Moonflesh — one of everything (including 1× each arcane and currency pack)
- 10,494 Moonflesh — buy out the whole shop at maximum limits
  (arcanes ×42 each, Kuva ×25, Credits ×100, Endo ×300)

## Sources

Prices and purchase limits from the
[official Warframe Wiki](https://wiki.warframe.com/w/Epoch_Operation:_Taubound)
(verified Oct 16, 2026); item list cross-checked against
[warframe.com](https://www.warframe.com/en/news/epoch-operation-taubound) and Shacknews.

Note: DE's announcement calls the 125-Moonflesh Somachord "Eris Mortem"; the wiki
shop lists that slot as "Devourer". Same item, same price.

Fan-made checklist, not affiliated with Digital Extremes. Plain HTML/CSS/JS in a
single `index.html` — no build step, no dependencies.
