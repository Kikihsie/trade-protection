# Trade Protection — interactive diagrams

Interactive diagrams for **IB DP Economics 4.2 / 4.3 — Types of trade protection**.

Four panels, one shared pair of demand and supply curves:

| Panel | Policy lever | Who ends up with area 3 |
|---|---|---|
| Tariff | per-unit tariff `t` | government tariff revenue |
| Import quota | import ceiling | quota rents (usually foreign exporters) |
| Production subsidy | per-unit subsidy `s` | nobody — becomes government spending |
| Export subsidy | per-unit subsidy `s` | nobody — areas a–d inside the panel |

Dragging a slider moves **only the curve that should move**; the rest stay still and
keep a grey dashed ghost of their original position. Welfare areas, before/after
guides, and a live panel of price, quantity, trade volume, CS / PS, budget and net
welfare are all toggleable.

## Model

- `Qd = 100 − 2P`, `Qs = 3P`
- autarky: `P* = 20`, `Q* = 60`
- importing country faces `Pw = 8` → free-trade imports of 60 units
- the export-subsidy panel uses the same curves against `Pw = 22` (above autarky),
  so the country exports `Q3 − Q2 = 10` units in free trade

Every shaded polygon is measured with the shoelace formula and cross-checked with a
point-in-polygon grid sweep, so the four areas tile the band between the world price
and the new price with no gaps and no overlaps.

## Use

`index.html` is fully self-contained — no CDN, no fonts, no images, no fetch. Open it
locally, or serve the folder with GitHub Pages.

## Source

`index.html` is the single source of truth. Edit it directly.
