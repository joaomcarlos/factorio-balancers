# Joao's Belt Balancer Collection — Turbo Edition

Every belt balancer you will ever need, **defaulted to turbo (green) belts**.

This repo merges the two definitive community balancer books into one sorted
collection, then upgrades every belt, underground belt and splitter to
**turbo** — no post-paste upgrading required. Paste, stamp, feed it stacked
turbo belts.

- **[Raynquist's balancer book (fall 2025)](https://github.com/raynquist/balancer)** — the canonical collection
- **[ChocPaint's BELT BALANCER COMPENDIUM V30.77](https://factoriobin.com/post/vqf3io)** — every variant, size and shape

Everything is sorted by function, then by input count: **belt balancers** in
`1 to x` … `16 to x` + `oversize`, then **lane balancers**, **lane splitters**,
downgrades, FAQ and tools. ChocPaint's compendium includes many designs sourced
from raynquist's book — those are **deduplicated**, so each design appears
once (raynquist's version kept). ChocPaint-unique variants — different
footprints, lane versions, sizes raynquist doesn't carry — sit next to the
canonical designs in the same sections, marked by their `[WxH]` tags.

<p align="center">
  <a href="https://factoriobin.com/post/2zezo8"><img src="images/raynquist__8_to_x__8-8_balancer.jpg" width="520" alt="8 → 8 turbo balancer"></a><br>
  <i>The classic 8 → 8, turbo'd.</i>
</p>

| | |
|---|---|
| Download | **[Combined book (FactorioBin)](https://factoriobin.com/post/2zezo8)** · [`belt-balancers-turbo.book.txt`](belt-balancers-turbo.book.txt) |
| Books individually | [raynquist turbo](strings/raynquist-fall-2025-turbo.txt) · [chocpaint turbo](strings/chocpaint-v3077-turbo.txt) · [raynquist original](strings/raynquist-fall-2025-original.txt) · [chocpaint original](strings/chocpaint-v3077-original.txt) |
| Blueprints | 293 unique balancers as individual strings in [`blueprints/`](blueprints/), decoded JSON in [`json/`](json/) |
| Renders | Every balancer rendered below (Factorio 2.1.11 sprites, dirt terrain) |

---

## How much does a balancer move?

A **turbo belt** moves 60 items/s. Fully stacked (4-high, Space Age belt
stacking) it moves **240 items/s**. A balancer can only move as much as its
inputs provide — so an `N → M` balancer fed by `N` fully-stacked turbo belts
moves **N stacked belts ≈ N × 240 items/s**. For almost every design here,
just count the inputs.

## Legend (ChocPaint tags)

| Tag | Meaning |
|---|---|
| UT | Unlimited throughput — always full throughput even when starved |
| Lane | Also balances both lanes of each belt |
| Corner | Output turns 90° |
| Edge | Inputs/outputs enter on the edges |
| Inline | Flow continues in a straight line |
| Split | Splits/merges outputs |
| ⚠ Unbalanced | Not perfectly balanced — flagged by the author |
| ☢ Residual | Items may stay on belts — flagged by the author |
| `[item=turbo-transport-belt]+` | Requires turbo belts for full throughput |

---

# Catalogue

# belt balancers

Every belt balancer, sorted by number of input belts.
raynquist canonical designs first per ratio, ChocPaint compendium variants ([WxH] tags) after.


## 1 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/chocpaint__1_to_x__1-2_2x1_UT.jpg" width="360"> | **1-2 [2x1] (UT)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-2_2x1_UT.txt) · chocpaint | **1 → 2**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput<br>Ha ha |
| <img src="images/chocpaint__1_to_x__1-2_3x4_UT_Lane_virtual-signal_signal-alert.jpg" width="360"> | **1-2 [3x4] (UT, Lane ⚠)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-2_3x4_UT_Lane_virtual-signal_signal-alert.txt) · chocpaint | **1 → 2**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput<br>lane-balanced<br>⚠ not fully balanced |
| <img src="images/chocpaint__1_to_x__1-2_3x6_UT_Lane_virtual-signal_signal-radioactivity.jpg" width="360"> | **1-2 [3x6] (UT, Lane,  ☢)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-2_3x6_UT_Lane_virtual-signal_signal-radioactivity.txt) · chocpaint | **1 → 2**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput<br>lane-balanced<br>☢ residual items possible |
| <img src="images/raynquist__1_to_x__1-3_TU_balancer.jpg" width="360"> | **1-3 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-3_TU_balancer.txt) | **1 → 3**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__1_to_x__1-4_TU_balancer.jpg" width="360"> | **1-4 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-4_TU_balancer.txt) | **1 → 4**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__1_to_x__1-5_TU_balancer.jpg" width="360"> | **1-5 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-5_TU_balancer.txt) | **1 → 5**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__1_to_x__1-5_5x6_UT.jpg" width="360"> | **1-5 [5x6] (UT)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-5_5x6_UT.txt) · chocpaint | **1 → 5**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput |
| <img src="images/raynquist__1_to_x__1-6_TU_balancer.jpg" width="360"> | **1-6 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-6_TU_balancer.txt) | **1 → 6**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__1_to_x__1-7_TU_balancer.jpg" width="360"> | **1-7 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-7_TU_balancer.txt) | **1 → 7**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__1_to_x__1-7_7x5_UT.jpg" width="360"> | **1-7 [7x5] (UT)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-7_7x5_UT.txt) · chocpaint | **1 → 7**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput |
| <img src="images/raynquist__1_to_x__1-8_TU_balancer.jpg" width="360"> | **1-8 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-8_TU_balancer.txt) | **1 → 8**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__1_to_x__1-9_TU_balancer.jpg" width="360"> | **1-9 TU balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-9_TU_balancer.txt) | **1 → 9**<br>1 stacked turbo belt<br>≈ 240 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__1_to_x__1-10_10x6_UT_Fractal.jpg" width="360"> | **1-10 [10x6] (UT, Fractal)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-10_10x6_UT_Fractal.txt) · chocpaint | **1 → 10**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput<br>fractal design |
| <img src="images/chocpaint__1_to_x__1-12_12x5_UT.jpg" width="360"> | **1-12 [12x5] (UT)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-12_12x5_UT.txt) · chocpaint | **1 → 12**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput |
| <img src="images/chocpaint__1_to_x__1-16_16x4_UT.jpg" width="360"> | **1-16 [16x4] (UT)**<br>[`bp`](blueprints/chocpaint__1_to_x__1-16_16x4_UT.txt) · chocpaint | **1 → 16**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput |
| <img src="images/raynquist__1_to_x__1-17_balancer.jpg" width="360"> | **1-17 balancer**<br>[`bp`](blueprints/raynquist__1_to_x__1-17_balancer.txt) | **1 → 17**<br>1 stacked turbo belt<br>≈ 240 items/s | — |

## 2 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/chocpaint__2_to_x__2-1_2x3_UT_Lane_virtual-signal_signal-alert_Corner.jpg" width="360"> | **2-1 [2x3] (UT, Lane ⚠, Corner)**<br>[`bp`](blueprints/chocpaint__2_to_x__2-1_2x3_UT_Lane_virtual-signal_signal-alert_Corner.txt) · chocpaint | **2 → 1**<br>2 stacked turbo belts<br>≈ 480 items/s | unlimited throughput<br>lane-balanced<br>output turns 90°<br>⚠ not fully balanced |
| <img src="images/chocpaint__2_to_x__2-1_3x3_UT_Lane_virtual-signal_signal-alert_Straight.jpg" width="360"> | **2-1 [3x3] (UT, Lane ⚠, Straight)**<br>[`bp`](blueprints/chocpaint__2_to_x__2-1_3x3_UT_Lane_virtual-signal_signal-alert_Straight.txt) · chocpaint | **2 → 1**<br>2 stacked turbo belts<br>≈ 480 items/s | unlimited throughput<br>lane-balanced<br>straight-through<br>⚠ not fully balanced |
| <img src="images/chocpaint__2_to_x__2-2_2x1_UT.jpg" width="360"> | **2-2 [2x1] (UT)**<br>[`bp`](blueprints/chocpaint__2_to_x__2-2_2x1_UT.txt) · chocpaint | **2 → 2**<br>2 stacked turbo belts<br>≈ 480 items/s | unlimited throughput<br>Ha ha |
| <img src="images/raynquist__2_to_x__2-3_TU_balancer.jpg" width="360"> | **2-3 TU balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-3_TU_balancer.txt) | **2 → 3**<br>2 stacked turbo belts<br>≈ 480 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__2_to_x__2-4_TU_balancer.jpg" width="360"> | **2-4 TU balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-4_TU_balancer.txt) | **2 → 4**<br>2 stacked turbo belts<br>≈ 480 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__2_to_x__2-4_balancer.jpg" width="360"> | **2-4 balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-4_balancer.txt) | **2 → 4**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/chocpaint__2_to_x__2-4_4x3_UT_virtual-signal_signal-alert_Compact.jpg" width="360"> | **2-4 [4x3] (UT ⚠, Compact)**<br>[`bp`](blueprints/chocpaint__2_to_x__2-4_4x3_UT_virtual-signal_signal-alert_Compact.txt) · chocpaint | **2 → 4**<br>2 stacked turbo belts<br>≈ 480 items/s | unlimited throughput<br>compact<br>⚠ not fully balanced<br>UT, assuming both inputs are already balanced |
| <img src="images/raynquist__2_to_x__2-5_balancer.jpg" width="360"> | **2-5 balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-5_balancer.txt) | **2 → 5**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/raynquist__2_to_x__2-6_balancer.jpg" width="360"> | **2-6 balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-6_balancer.txt) | **2 → 6**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/raynquist__2_to_x__2-7_balancer.jpg" width="360"> | **2-7 balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-7_balancer.txt) | **2 → 7**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/chocpaint__2_to_x__2-7_7x6.jpg" width="360"> | **2-7 [7x6]**<br>[`bp`](blueprints/chocpaint__2_to_x__2-7_7x6.txt) · chocpaint | **2 → 7**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/raynquist__2_to_x__2-8_TU_balancer.jpg" width="360"> | **2-8 TU balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-8_TU_balancer.txt) | **2 → 8**<br>2 stacked turbo belts<br>≈ 480 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__2_to_x__2-8_balancer.jpg" width="360"> | **2-8 balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-8_balancer.txt) | **2 → 8**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/raynquist__2_to_x__2-9_balancer.jpg" width="360"> | **2-9 balancer**<br>[`bp`](blueprints/raynquist__2_to_x__2-9_balancer.txt) | **2 → 9**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/chocpaint__2_to_x__2-10_10x6_Fractal.jpg" width="360"> | **2-10 [10x6] (Fractal)**<br>[`bp`](blueprints/chocpaint__2_to_x__2-10_10x6_Fractal.txt) · chocpaint | **2 → 10**<br>2 stacked turbo belts<br>≈ 480 items/s | fractal design |
| <img src="images/chocpaint__2_to_x__2-12_12x6.jpg" width="360"> | **2-12 [12x6]**<br>[`bp`](blueprints/chocpaint__2_to_x__2-12_12x6.txt) · chocpaint | **2 → 12**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/chocpaint__2_to_x__2-16_16x4.jpg" width="360"> | **2-16 [16x4]**<br>[`bp`](blueprints/chocpaint__2_to_x__2-16_16x4.txt) · chocpaint | **2 → 16**<br>2 stacked turbo belts<br>≈ 480 items/s | — |

## 3 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__3_to_x__3-1_TU_balancer.jpg" width="360"> | **3-1 TU balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-1_TU_balancer.txt) | **3 → 1**<br>3 stacked turbo belts<br>≈ 720 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__3_to_x__3-1_4x5_UT.jpg" width="360"> | **3-1 [4x5] (UT)**<br>[`bp`](blueprints/chocpaint__3_to_x__3-1_4x5_UT.txt) · chocpaint | **3 → 1**<br>3 stacked turbo belts<br>≈ 720 items/s | unlimited throughput |
| <img src="images/raynquist__3_to_x__3-2_TU_balancer.jpg" width="360"> | **3-2 TU balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-2_TU_balancer.txt) | **3 → 2**<br>3 stacked turbo belts<br>≈ 720 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__3_to_x__3-2_4x6_UT.jpg" width="360"> | **3-2 [4x6] (UT)**<br>[`bp`](blueprints/chocpaint__3_to_x__3-2_4x6_UT.txt) · chocpaint | **3 → 2**<br>3 stacked turbo belts<br>≈ 720 items/s | unlimited throughput |
| <img src="images/raynquist__3_to_x__3-3_TU_balancer.jpg" width="360"> | **3-3 TU balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-3_TU_balancer.txt) | **3 → 3**<br>3 stacked turbo belts<br>≈ 720 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__3_to_x__3-3_TU_corner_balancer.jpg" width="360"> | **3-3 TU corner balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-3_TU_corner_balancer.txt) | **3 → 3**<br>3 stacked turbo belts<br>≈ 720 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__3_to_x__3-3_5x6.jpg" width="360"> | **3-3 [5x6]**<br>[`bp`](blueprints/chocpaint__3_to_x__3-3_5x6.txt) · chocpaint | **3 → 3**<br>3 stacked turbo belts<br>≈ 720 items/s | — |
| <img src="images/raynquist__3_to_x__3-4_TU_balancer.jpg" width="360"> | **3-4 TU balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-4_TU_balancer.txt) | **3 → 4**<br>3 stacked turbo belts<br>≈ 720 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__3_to_x__3-5_balancer.jpg" width="360"> | **3-5 balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-5_balancer.txt) | **3 → 5**<br>3 stacked turbo belts<br>≈ 720 items/s | — |
| <img src="images/chocpaint__3_to_x__3-5_7x10_UT.jpg" width="360"> | **3-5 [7x10] (UT)**<br>[`bp`](blueprints/chocpaint__3_to_x__3-5_7x10_UT.txt) · chocpaint | **3 → 5**<br>3 stacked turbo belts<br>≈ 720 items/s | unlimited throughput |
| <img src="images/raynquist__3_to_x__3-6_TU_balancer.jpg" width="360"> | **3-6 TU balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-6_TU_balancer.txt) | **3 → 6**<br>3 stacked turbo belts<br>≈ 720 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__3_to_x__3-6_balancer.jpg" width="360"> | **3-6 balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-6_balancer.txt) | **3 → 6**<br>3 stacked turbo belts<br>≈ 720 items/s | — |
| <img src="images/raynquist__3_to_x__3-7_balancer.jpg" width="360"> | **3-7 balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-7_balancer.txt) | **3 → 7**<br>3 stacked turbo belts<br>≈ 720 items/s | — |
| <img src="images/chocpaint__3_to_x__3-7_9x7_Mid.jpg" width="360"> | **3-7 [9x7] (Mid)**<br>[`bp`](blueprints/chocpaint__3_to_x__3-7_9x7_Mid.txt) · chocpaint | **3 → 7**<br>3 stacked turbo belts<br>≈ 720 items/s | — |
| <img src="images/raynquist__3_to_x__3-8_balancer.jpg" width="360"> | **3-8 balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-8_balancer.txt) | **3 → 8**<br>3 stacked turbo belts<br>≈ 720 items/s | — |
| <img src="images/raynquist__3_to_x__3-9_balancer.jpg" width="360"> | **3-9 balancer**<br>[`bp`](blueprints/raynquist__3_to_x__3-9_balancer.txt) | **3 → 9**<br>3 stacked turbo belts<br>≈ 720 items/s | — |

## 4 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__4_to_x__4-1_TU_balancer.jpg" width="360"> | **4-1 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-1_TU_balancer.txt) | **4 → 1**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__4_to_x__4-1_4x4_UT_Lane_virtual-signal_signal-alert_Corner.jpg" width="360"> | **4-1 [4x4] (UT, Lane ⚠, Corner)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-1_4x4_UT_Lane_virtual-signal_signal-alert_Corner.txt) · chocpaint | **4 → 1**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput<br>lane-balanced<br>output turns 90°<br>⚠ not fully balanced |
| <img src="images/chocpaint__4_to_x__4-1_4x4_UT_Lane_virtual-signal_signal-alert_Straight.jpg" width="360"> | **4-1 [4x4] (UT, Lane ⚠, Straight)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-1_4x4_UT_Lane_virtual-signal_signal-alert_Straight.txt) · chocpaint | **4 → 1**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput<br>lane-balanced<br>straight-through<br>⚠ not fully balanced |
| <img src="images/raynquist__4_to_x__4-2_TU_balancer.jpg" width="360"> | **4-2 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-2_TU_balancer.txt) | **4 → 2**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__4_to_x__4-2_balancer.jpg" width="360"> | **4-2 balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-2_balancer.txt) | **4 → 2**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/raynquist__4_to_x__4-3_TU_balancer.jpg" width="360"> | **4-3 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-3_TU_balancer.txt) | **4 → 3**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__4_to_x__4-3_6x6.jpg" width="360"> | **4-3 [6x6]**<br>[`bp`](blueprints/chocpaint__4_to_x__4-3_6x6.txt) · chocpaint | **4 → 3**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/chocpaint__4_to_x__4-3_7x7_UT.jpg" width="360"> | **4-3 [7x7] (UT)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-3_7x7_UT.txt) · chocpaint | **4 → 3**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput |
| <img src="images/raynquist__4_to_x__4-4_TU_balancer.jpg" width="360"> | **4-4 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-4_TU_balancer.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__4_to_x__4-4_TU_corner_balancer.jpg" width="360"> | **4-4 TU corner balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-4_TU_corner_balancer.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__4_to_x__4-4_TU_merge_balancer.jpg" width="360"> | **4-4 TU merge balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-4_TU_merge_balancer.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__4_to_x__4-4_TU_split_balancer.jpg" width="360"> | **4-4 TU split balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-4_TU_split_balancer.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__4_to_x__4-4_4x8_UT.jpg" width="360"> | **4-4 [4x8] (UT)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-4_4x8_UT.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput |
| <img src="images/chocpaint__4_to_x__4-4_6x7_UT_Corner_Compact-Tall.jpg" width="360"> | **4-4 [6x7] (UT, Corner, Compact-Tall)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-4_6x7_UT_Corner_Compact-Tall.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput<br>output turns 90° |
| <img src="images/chocpaint__4_to_x__4-4_8x5_UT_Corner_Compact-Wide.jpg" width="360"> | **4-4 [8x5] (UT, Corner, Compact-Wide)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-4_8x5_UT_Corner_Compact-Wide.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput<br>output turns 90° |
| <img src="images/raynquist__4_to_x__4-5_balancer.jpg" width="360"> | **4-5 balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-5_balancer.txt) | **4 → 5**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/chocpaint__4_to_x__4-5_8x9.jpg" width="360"> | **4-5 [8x9]**<br>[`bp`](blueprints/chocpaint__4_to_x__4-5_8x9.txt) · chocpaint | **4 → 5**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/raynquist__4_to_x__4-6_TU_balancer.jpg" width="360"> | **4-6 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-6_TU_balancer.txt) | **4 → 6**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__4_to_x__4-6_balancer.jpg" width="360"> | **4-6 balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-6_balancer.txt) | **4 → 6**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/chocpaint__4_to_x__4-6_8x10_UT.jpg" width="360"> | **4-6 [8x10] (UT)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-6_8x10_UT.txt) · chocpaint | **4 → 6**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput |
| <img src="images/raynquist__4_to_x__4-7_balancer.jpg" width="360"> | **4-7 balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-7_balancer.txt) | **4 → 7**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/raynquist__4_to_x__4-8_TU_balancer.jpg" width="360"> | **4-8 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-8_TU_balancer.txt) | **4 → 8**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__4_to_x__4-8_balancer.jpg" width="360"> | **4-8 balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-8_balancer.txt) | **4 → 8**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/chocpaint__4_to_x__4-8_8x10_UT.jpg" width="360"> | **4-8 [8x10] (UT)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-8_8x10_UT.txt) · chocpaint | **4 → 8**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput |
| <img src="images/raynquist__4_to_x__4-9_balancer.jpg" width="360"> | **4-9 balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-9_balancer.txt) | **4 → 9**<br>4 stacked turbo belts<br>≈ 960 items/s | — |
| <img src="images/chocpaint__4_to_x__4-10_10x7_Unbalanced_Fractal.jpg" width="360"> | **4-10 [10x7] (Unbalanced, Fractal)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-10_10x7_Unbalanced_Fractal.txt) · chocpaint | **4 → 10**<br>4 stacked turbo belts<br>≈ 960 items/s | not fully balanced<br>fractal design |
| <img src="images/chocpaint__4_to_x__4-10_12x15_UT.jpg" width="360"> | **4-10 [12x15] (UT)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-10_12x15_UT.txt) · chocpaint | **4 → 10**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput |
| <img src="images/raynquist__4_to_x__4-12_TU_balancer.jpg" width="360"> | **4-12 TU balancer**<br>[`bp`](blueprints/raynquist__4_to_x__4-12_TU_balancer.txt) | **4 → 12**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__4_to_x__4-12_12x14_UT.jpg" width="360"> | **4-12 [12x14] (UT)**<br>[`bp`](blueprints/chocpaint__4_to_x__4-12_12x14_UT.txt) · chocpaint | **4 → 12**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput |
| <img src="images/chocpaint__4_to_x__4-16_16x5.jpg" width="360"> | **4-16 [16x5]**<br>[`bp`](blueprints/chocpaint__4_to_x__4-16_16x5.txt) · chocpaint | **4 → 16**<br>4 stacked turbo belts<br>≈ 960 items/s | — |

## 5 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__5_to_x__5-1_TU_balancer.jpg" width="360"> | **5-1 TU balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-1_TU_balancer.txt) | **5 → 1**<br>5 stacked turbo belts<br>≈ 1,200 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__5_to_x__5-2_balancer.jpg" width="360"> | **5-2 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-2_balancer.txt) | **5 → 2**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/chocpaint__5_to_x__5-2_5x7.jpg" width="360"> | **5-2 [5x7]**<br>[`bp`](blueprints/chocpaint__5_to_x__5-2_5x7.txt) · chocpaint | **5 → 2**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-3_balancer.jpg" width="360"> | **5-3 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-3_balancer.txt) | **5 → 3**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/chocpaint__5_to_x__5-3_8x8.jpg" width="360"> | **5-3 [8x8]**<br>[`bp`](blueprints/chocpaint__5_to_x__5-3_8x8.txt) · chocpaint | **5 → 3**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-4_balancer.jpg" width="360"> | **5-4 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-4_balancer.txt) | **5 → 4**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-5_balancer.jpg" width="360"> | **5-5 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-5_balancer.txt) | **5 → 5**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/chocpaint__5_to_x__5-5_5x15_Inline.jpg" width="360"> | **5-5 [5x15] (Inline)**<br>[`bp`](blueprints/chocpaint__5_to_x__5-5_5x15_Inline.txt) · chocpaint | **5 → 5**<br>5 stacked turbo belts<br>≈ 1,200 items/s | inline |
| <img src="images/chocpaint__5_to_x__5-5_7x10.jpg" width="360"> | **5-5 [7x10]**<br>[`bp`](blueprints/chocpaint__5_to_x__5-5_7x10.txt) · chocpaint | **5 → 5**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-6_balancer.jpg" width="360"> | **5-6 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-6_balancer.txt) | **5 → 6**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-7_balancer.jpg" width="360"> | **5-7 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-7_balancer.txt) | **5 → 7**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-8_balancer.jpg" width="360"> | **5-8 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-8_balancer.txt) | **5 → 8**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__5_to_x__5-9_balancer.jpg" width="360"> | **5-9 balancer**<br>[`bp`](blueprints/raynquist__5_to_x__5-9_balancer.txt) | **5 → 9**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/chocpaint__5_to_x__5-9_9x16_item_turbo-transport-belt.jpg" width="360"> | **5-9 [9x16] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__5_to_x__5-9_9x16_item_turbo-transport-belt.txt) · chocpaint | **5 → 9**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/chocpaint__5_to_x__5-10_10x11_Fractal_Unbalanced.jpg" width="360"> | **5-10 [10x11] (Fractal, Unbalanced)**<br>[`bp`](blueprints/chocpaint__5_to_x__5-10_10x11_Fractal_Unbalanced.txt) · chocpaint | **5 → 10**<br>5 stacked turbo belts<br>≈ 1,200 items/s | fractal design<br>not fully balanced |

## 6 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__6_to_x__6-1_TU_balancer.jpg" width="360"> | **6-1 TU balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-1_TU_balancer.txt) | **6 → 1**<br>6 stacked turbo belts<br>≈ 1,440 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__6_to_x__6-1_6x5_UT.jpg" width="360"> | **6-1 [6x5] (UT)**<br>[`bp`](blueprints/chocpaint__6_to_x__6-1_6x5_UT.txt) · chocpaint | **6 → 1**<br>6 stacked turbo belts<br>≈ 1,440 items/s | unlimited throughput |
| <img src="images/raynquist__6_to_x__6-2_balancer.jpg" width="360"> | **6-2 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-2_balancer.txt) | **6 → 2**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-3_TU_balancer.jpg" width="360"> | **6-3 TU balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-3_TU_balancer.txt) | **6 → 3**<br>6 stacked turbo belts<br>≈ 1,440 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__6_to_x__6-3_balancer.jpg" width="360"> | **6-3 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-3_balancer.txt) | **6 → 3**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/chocpaint__6_to_x__6-3_7x5.jpg" width="360"> | **6-3 [7x5]**<br>[`bp`](blueprints/chocpaint__6_to_x__6-3_7x5.txt) · chocpaint | **6 → 3**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-4_TU_balancer.jpg" width="360"> | **6-4 TU balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-4_TU_balancer.txt) | **6 → 4**<br>6 stacked turbo belts<br>≈ 1,440 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__6_to_x__6-4_balancer.jpg" width="360"> | **6-4 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-4_balancer.txt) | **6 → 4**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-5_balancer.jpg" width="360"> | **6-5 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-5_balancer.txt) | **6 → 5**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-6_balancer.jpg" width="360"> | **6-6 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-6_balancer.txt) | **6 → 6**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-6_corner_balancer.jpg" width="360"> | **6-6 corner balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-6_corner_balancer.txt) | **6 → 6**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/chocpaint__6_to_x__6-6_7x10_item_turbo-transport-belt.jpg" width="360"> | **6-6 [7x10] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__6_to_x__6-6_7x10_item_turbo-transport-belt.txt) · chocpaint | **6 → 6**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-7_balancer.jpg" width="360"> | **6-7 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-7_balancer.txt) | **6 → 7**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/chocpaint__6_to_x__6-7_9x13.jpg" width="360"> | **6-7 [9x13]**<br>[`bp`](blueprints/chocpaint__6_to_x__6-7_9x13.txt) · chocpaint | **6 → 7**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-8_balancer.jpg" width="360"> | **6-8 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-8_balancer.txt) | **6 → 8**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/chocpaint__6_to_x__6-8_8x11_Mid_item_turbo-transport-belt.jpg" width="360"> | **6-8 [8x11] (Mid, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__6_to_x__6-8_8x11_Mid_item_turbo-transport-belt.txt) · chocpaint | **6 → 8**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__6_to_x__6-9_balancer.jpg" width="360"> | **6-9 balancer**<br>[`bp`](blueprints/raynquist__6_to_x__6-9_balancer.txt) | **6 → 9**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/chocpaint__6_to_x__6-9_9x14_item_turbo-transport-belt.jpg" width="360"> | **6-9 [9x14] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__6_to_x__6-9_9x14_item_turbo-transport-belt.txt) · chocpaint | **6 → 9**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |

## 7 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__7_to_x__7-1_TU_balancer.jpg" width="360"> | **7-1 TU balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-1_TU_balancer.txt) | **7 → 1**<br>7 stacked turbo belts<br>≈ 1,680 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__7_to_x__7-2_balancer.jpg" width="360"> | **7-2 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-2_balancer.txt) | **7 → 2**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-2_7x5.jpg" width="360"> | **7-2 [7x5]**<br>[`bp`](blueprints/chocpaint__7_to_x__7-2_7x5.txt) · chocpaint | **7 → 2**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-3_balancer.jpg" width="360"> | **7-3 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-3_balancer.txt) | **7 → 3**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-3_9x8.jpg" width="360"> | **7-3 [9x8]**<br>[`bp`](blueprints/chocpaint__7_to_x__7-3_9x8.txt) · chocpaint | **7 → 3**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-4_balancer.jpg" width="360"> | **7-4 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-4_balancer.txt) | **7 → 4**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-5_balancer.jpg" width="360"> | **7-5 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-5_balancer.txt) | **7 → 5**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-5_9x13.jpg" width="360"> | **7-5 [9x13]**<br>[`bp`](blueprints/chocpaint__7_to_x__7-5_9x13.txt) · chocpaint | **7 → 5**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-6_balancer.jpg" width="360"> | **7-6 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-6_balancer.txt) | **7 → 6**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-6_9x13.jpg" width="360"> | **7-6 [9x13]**<br>[`bp`](blueprints/chocpaint__7_to_x__7-6_9x13.txt) · chocpaint | **7 → 6**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-7_balancer.jpg" width="360"> | **7-7 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-7_balancer.txt) | **7 → 7**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-8_balancer.jpg" width="360"> | **7-8 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-8_balancer.txt) | **7 → 8**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-8_8x14_item_turbo-transport-belt.jpg" width="360"> | **7-8 [8x14] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__7_to_x__7-8_8x14_item_turbo-transport-belt.txt) · chocpaint | **7 → 8**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-8_9x13_item_turbo-transport-belt.jpg" width="360"> | **7-8 [9x13] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__7_to_x__7-8_9x13_item_turbo-transport-belt.txt) · chocpaint | **7 → 8**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-9_balancer.jpg" width="360"> | **7-9 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-9_balancer.txt) | **7 → 9**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/chocpaint__7_to_x__7-9_12x16_item_turbo-transport-belt.jpg" width="360"> | **7-9 [12x16] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__7_to_x__7-9_12x16_item_turbo-transport-belt.txt) · chocpaint | **7 → 9**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-10_balancer.jpg" width="360"> | **7-10 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-10_balancer.txt) | **7 → 10**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__7_to_x__7-13_balancer.jpg" width="360"> | **7-13 balancer**<br>[`bp`](blueprints/raynquist__7_to_x__7-13_balancer.txt) | **7 → 13**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |

## 8 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__8_to_x__8-1_TU_balancer.jpg" width="360"> | **8-1 TU balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-1_TU_balancer.txt) | **8 → 1**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__8_to_x__8-1_8x4_UT_Lane_virtual-signal_signal-alert.jpg" width="360"> | **8-1 [8x4] (UT, Lane ⚠)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-1_8x4_UT_Lane_virtual-signal_signal-alert.txt) · chocpaint | **8 → 1**<br>8 stacked turbo belts<br>≈ 1,920 items/s | unlimited throughput<br>lane-balanced<br>⚠ not fully balanced |
| <img src="images/raynquist__8_to_x__8-2_TU_balancer.jpg" width="360"> | **8-2 TU balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-2_TU_balancer.txt) | **8 → 2**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__8_to_x__8-2_balancer.jpg" width="360"> | **8-2 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-2_balancer.txt) | **8 → 2**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-2_8x4_Lane_virtual-signal_signal-alert.jpg" width="360"> | **8-2 [8x4] (Lane ⚠)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-2_8x4_Lane_virtual-signal_signal-alert.txt) · chocpaint | **8 → 2**<br>8 stacked turbo belts<br>≈ 1,920 items/s | lane-balanced<br>⚠ not fully balanced |
| <img src="images/raynquist__8_to_x__8-3_balancer.jpg" width="360"> | **8-3 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-3_balancer.txt) | **8 → 3**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-3_8x8.jpg" width="360"> | **8-3 [8x8]**<br>[`bp`](blueprints/chocpaint__8_to_x__8-3_8x8.txt) · chocpaint | **8 → 3**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-4_TU_balancer.jpg" width="360"> | **8-4 TU balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-4_TU_balancer.txt) | **8 → 4**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__8_to_x__8-4_balancer.jpg" width="360"> | **8-4 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-4_balancer.txt) | **8 → 4**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-5_balancer.jpg" width="360"> | **8-5 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-5_balancer.txt) | **8 → 5**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-5_8x12.jpg" width="360"> | **8-5 [8x12]**<br>[`bp`](blueprints/chocpaint__8_to_x__8-5_8x12.txt) · chocpaint | **8 → 5**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-5_8x13_item_turbo-transport-belt.jpg" width="360"> | **8-5 [8x13] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-5_8x13_item_turbo-transport-belt.txt) · chocpaint | **8 → 5**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-6_balancer.jpg" width="360"> | **8-6 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-6_balancer.txt) | **8 → 6**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-6_8x11.jpg" width="360"> | **8-6 [8x11]**<br>[`bp`](blueprints/chocpaint__8_to_x__8-6_8x11.txt) · chocpaint | **8 → 6**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-7_balancer.jpg" width="360"> | **8-7 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-7_balancer.txt) | **8 → 7**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-8_TU_balancer.jpg" width="360"> | **8-8 TU balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-8_TU_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__8_to_x__8-8_balancer.jpg" width="360"> | **8-8 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-8_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-8_corner_balancer.jpg" width="360"> | **8-8 corner balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-8_corner_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-8_merge_balancer.jpg" width="360"> | **8-8 merge balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-8_merge_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-8_split_balancer.jpg" width="360"> | **8-8 split balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-8_split_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-8_10x15_UT_Split-2_item_turbo-transport-belt.jpg" width="360"> | **8-8 [10x15] (UT, Split-2, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-8_10x15_UT_Split-2_item_turbo-transport-belt.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | unlimited throughput |
| <img src="images/chocpaint__8_to_x__8-8_11x8_Edge-In.jpg" width="360"> | **8-8 [11x8] (Edge-In)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-8_11x8_Edge-In.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-8_11x8_Split-2.jpg" width="360"> | **8-8 [11x8] (Split-2)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-8_11x8_Split-2.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-8_12x8_Split-4.jpg" width="360"> | **8-8 [12x8] (Split-4)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-8_12x8_Split-4.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-8_8x15_Fractal.jpg" width="360"> | **8-8 [8x15] (Fractal)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-8_8x15_Fractal.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | fractal design |
| <img src="images/chocpaint__8_to_x__8-8_8x16_UT_item_turbo-transport-belt.jpg" width="360"> | **8-8 [8x16] (UT, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-8_8x16_UT_item_turbo-transport-belt.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | unlimited throughput |
| <img src="images/raynquist__8_to_x__8-9_balancer.jpg" width="360"> | **8-9 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-9_balancer.txt) | **8 → 9**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-9_11x14_item_turbo-transport-belt.jpg" width="360"> | **8-9 [11x14] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-9_11x14_item_turbo-transport-belt.txt) · chocpaint | **8 → 9**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-9_9x17_item_turbo-transport-belt.jpg" width="360"> | **8-9 [9x17] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-9_9x17_item_turbo-transport-belt.txt) · chocpaint | **8 → 9**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-10_balancer.jpg" width="360"> | **8-10 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-10_balancer.txt) | **8 → 10**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-10_10x14_item_turbo-transport-belt.jpg" width="360"> | **8-10 [10x14] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-10_10x14_item_turbo-transport-belt.txt) · chocpaint | **8 → 10**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-12_balancer.jpg" width="360"> | **8-12 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-12_balancer.txt) | **8 → 12**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-12_12x12_item_turbo-transport-belt.jpg" width="360"> | **8-12 [12x12] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-12_12x12_item_turbo-transport-belt.txt) · chocpaint | **8 → 12**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__8_to_x__8-13_balancer.jpg" width="360"> | **8-13 balancer**<br>[`bp`](blueprints/raynquist__8_to_x__8-13_balancer.txt) | **8 → 13**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-13_15x13_item_turbo-transport-belt.jpg" width="360"> | **8-13 [15x13] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__8_to_x__8-13_15x13_item_turbo-transport-belt.txt) · chocpaint | **8 → 13**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/chocpaint__8_to_x__8-16_16x8.jpg" width="360"> | **8-16 [16x8]**<br>[`bp`](blueprints/chocpaint__8_to_x__8-16_16x8.txt) · chocpaint | **8 → 16**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |

## 9 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__9_to_x__9-1_TU_balancer.jpg" width="360"> | **9-1 TU balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-1_TU_balancer.txt) | **9 → 1**<br>9 stacked turbo belts<br>≈ 2,160 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__9_to_x__9-2_balancer.jpg" width="360"> | **9-2 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-2_balancer.txt) | **9 → 2**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/chocpaint__9_to_x__9-2_10x7.jpg" width="360"> | **9-2 [10x7]**<br>[`bp`](blueprints/chocpaint__9_to_x__9-2_10x7.txt) · chocpaint | **9 → 2**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-3_balancer.jpg" width="360"> | **9-3 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-3_balancer.txt) | **9 → 3**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/chocpaint__9_to_x__9-3_10x8.jpg" width="360"> | **9-3 [10x8]**<br>[`bp`](blueprints/chocpaint__9_to_x__9-3_10x8.txt) · chocpaint | **9 → 3**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-4_balancer.jpg" width="360"> | **9-4 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-4_balancer.txt) | **9 → 4**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/chocpaint__9_to_x__9-4_9x10.jpg" width="360"> | **9-4 [9x10]**<br>[`bp`](blueprints/chocpaint__9_to_x__9-4_9x10.txt) · chocpaint | **9 → 4**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-5_balancer.jpg" width="360"> | **9-5 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-5_balancer.txt) | **9 → 5**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-6_balancer.jpg" width="360"> | **9-6 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-6_balancer.txt) | **9 → 6**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/chocpaint__9_to_x__9-6_9x14_item_turbo-transport-belt.jpg" width="360"> | **9-6 [9x14] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__9_to_x__9-6_9x14_item_turbo-transport-belt.txt) · chocpaint | **9 → 6**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-7_balancer.jpg" width="360"> | **9-7 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-7_balancer.txt) | **9 → 7**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-8_balancer.jpg" width="360"> | **9-8 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-8_balancer.txt) | **9 → 8**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-9_balancer.jpg" width="360"> | **9-9 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-9_balancer.txt) | **9 → 9**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-10_balancer.jpg" width="360"> | **9-10 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-10_balancer.txt) | **9 → 10**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__9_to_x__9-12_balancer.jpg" width="360"> | **9-12 balancer**<br>[`bp`](blueprints/raynquist__9_to_x__9-12_balancer.txt) | **9 → 12**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/chocpaint__9_to_x__9-12_12x16.jpg" width="360"> | **9-12 [12x16]**<br>[`bp`](blueprints/chocpaint__9_to_x__9-12_12x16.txt) · chocpaint | **9 → 12**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |

## 10 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__10_to_x__10-8_balancer.jpg" width="360"> | **10-8 balancer**<br>[`bp`](blueprints/raynquist__10_to_x__10-8_balancer.txt) | **10 → 8**<br>10 stacked turbo belts<br>≈ 2,400 items/s | — |
| <img src="images/raynquist__10_to_x__10-10_balancer.jpg" width="360"> | **10-10 balancer**<br>[`bp`](blueprints/raynquist__10_to_x__10-10_balancer.txt) | **10 → 10**<br>10 stacked turbo belts<br>≈ 2,400 items/s | — |
| <img src="images/chocpaint__10_to_x__10-10_11x15_item_turbo-transport-belt.jpg" width="360"> | **10-10 [11x15] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__10_to_x__10-10_11x15_item_turbo-transport-belt.txt) · chocpaint | **10 → 10**<br>10 stacked turbo belts<br>≈ 2,400 items/s | — |
| <img src="images/chocpaint__10_to_x__10-12_10x20_item_turbo-transport-belt.jpg" width="360"> | **10-12 [10x20] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__10_to_x__10-12_10x20_item_turbo-transport-belt.txt) · chocpaint | **10 → 12**<br>10 stacked turbo belts<br>≈ 2,400 items/s | — |

## 11 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__11_to_x__11-10_balancer.jpg" width="360"> | **11-10 balancer**<br>[`bp`](blueprints/raynquist__11_to_x__11-10_balancer.txt) | **11 → 10**<br>11 stacked turbo belts<br>≈ 2,640 items/s | — |

## 12 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__12_to_x__12-4_TU_balancer.jpg" width="360"> | **12-4 TU balancer**<br>[`bp`](blueprints/raynquist__12_to_x__12-4_TU_balancer.txt) | **12 → 4**<br>12 stacked turbo belts<br>≈ 2,880 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__12_to_x__12-4_12x14_UT_item_turbo-transport-belt.jpg" width="360"> | **12-4 [12x14] (UT, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__12_to_x__12-4_12x14_UT_item_turbo-transport-belt.txt) · chocpaint | **12 → 4**<br>12 stacked turbo belts<br>≈ 2,880 items/s | unlimited throughput |
| <img src="images/chocpaint__12_to_x__12-8_12x18_item_turbo-transport-belt.jpg" width="360"> | **12-8 [12x18] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__12_to_x__12-8_12x18_item_turbo-transport-belt.txt) · chocpaint | **12 → 8**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/raynquist__12_to_x__12-10_balancer.jpg" width="360"> | **12-10 balancer**<br>[`bp`](blueprints/raynquist__12_to_x__12-10_balancer.txt) | **12 → 10**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/chocpaint__12_to_x__12-10_12x20_item_turbo-transport-belt.jpg" width="360"> | **12-10 [12x20] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__12_to_x__12-10_12x20_item_turbo-transport-belt.txt) · chocpaint | **12 → 10**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/raynquist__12_to_x__12-12_balancer.jpg" width="360"> | **12-12 balancer**<br>[`bp`](blueprints/raynquist__12_to_x__12-12_balancer.txt) | **12 → 12**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/chocpaint__12_to_x__12-12_14x15_item_turbo-transport-belt.jpg" width="360"> | **12-12 [14x15] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__12_to_x__12-12_14x15_item_turbo-transport-belt.txt) · chocpaint | **12 → 12**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/chocpaint__12_to_x__12-12_22x12_Split-3.jpg" width="360"> | **12-12 [22x12] (Split-3)**<br>[`bp`](blueprints/chocpaint__12_to_x__12-12_22x12_Split-3.txt) · chocpaint | **12 → 12**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/raynquist__12_to_x__12-25_balancer.jpg" width="360"> | **12-25 balancer**<br>[`bp`](blueprints/raynquist__12_to_x__12-25_balancer.txt) | **12 → 25**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |
| <img src="images/chocpaint__12_to_x__12-25_25x17_item_turbo-transport-belt.jpg" width="360"> | **12-25 [25x17] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__12_to_x__12-25_25x17_item_turbo-transport-belt.txt) · chocpaint | **12 → 25**<br>12 stacked turbo belts<br>≈ 2,880 items/s | — |

## 15 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__15_to_x__15-6_balancer.jpg" width="360"> | **15-6 balancer**<br>[`bp`](blueprints/raynquist__15_to_x__15-6_balancer.txt) | **15 → 6**<br>15 stacked turbo belts<br>≈ 3,600 items/s | — |
| <img src="images/raynquist__15_to_x__15-10_balancer.jpg" width="360"> | **15-10 balancer**<br>[`bp`](blueprints/raynquist__15_to_x__15-10_balancer.txt) | **15 → 10**<br>15 stacked turbo belts<br>≈ 3,600 items/s | — |
| <img src="images/chocpaint__15_to_x__15-10_15x17.jpg" width="360"> | **15-10 [15x17]**<br>[`bp`](blueprints/chocpaint__15_to_x__15-10_15x17.txt) · chocpaint | **15 → 10**<br>15 stacked turbo belts<br>≈ 3,600 items/s | — |

## 16 to x

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__16_to_x__16-8_TU_balancer.jpg" width="360"> | **16-8 TU balancer**<br>[`bp`](blueprints/raynquist__16_to_x__16-8_TU_balancer.txt) | **16 → 8**<br>16 stacked turbo belts<br>≈ 3,840 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/chocpaint__16_to_x__16-8_16x8_Split-2.jpg" width="360"> | **16-8 [16x8] (Split-2)**<br>[`bp`](blueprints/chocpaint__16_to_x__16-8_16x8_Split-2.txt) · chocpaint | **16 → 8**<br>16 stacked turbo belts<br>≈ 3,840 items/s | — |
| <img src="images/raynquist__16_to_x__16-10_balancer.jpg" width="360"> | **16-10 balancer**<br>[`bp`](blueprints/raynquist__16_to_x__16-10_balancer.txt) | **16 → 10**<br>16 stacked turbo belts<br>≈ 3,840 items/s | — |
| <img src="images/raynquist__16_to_x__16-16_balancer.jpg" width="360"> | **16-16 balancer**<br>[`bp`](blueprints/raynquist__16_to_x__16-16_balancer.txt) | **16 → 16**<br>16 stacked turbo belts<br>≈ 3,840 items/s | — |
| <img src="images/chocpaint__16_to_x__16-16_16x26_Fractal_item_turbo-transport-belt.jpg" width="360"> | **16-16 [16x26] (Fractal, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__16_to_x__16-16_16x26_Fractal_item_turbo-transport-belt.txt) · chocpaint | **16 → 16**<br>16 stacked turbo belts<br>≈ 3,840 items/s | fractal design |
| <img src="images/chocpaint__16_to_x__16-16_16x29_UT_item_turbo-transport-belt.jpg" width="360"> | **16-16 [16x29] (UT, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__16_to_x__16-16_16x29_UT_item_turbo-transport-belt.txt) · chocpaint | **16 → 16**<br>16 stacked turbo belts<br>≈ 3,840 items/s | unlimited throughput |

## oversize (20-128)

Balancers with 20 or more input belts.


| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__oversize_20-128___20-15_balancer.jpg" width="360"> | **20-15 balancer**<br>[`bp`](blueprints/raynquist__oversize_20-128___20-15_balancer.txt) | **20 → 15**<br>20 stacked turbo belts<br>≈ 4,800 items/s | — |
| <img src="images/chocpaint__oversize_20-128___20-15_item_turbo-transport-belt.jpg" width="360"> | **20-15 (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___20-15_item_turbo-transport-belt.txt) · chocpaint | **20 → 15**<br>20 stacked turbo belts<br>≈ 4,800 items/s | — |
| <img src="images/chocpaint__oversize_20-128___20-20_24x39_item_turbo-transport-belt.jpg" width="360"> | **20-20 [24x39] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___20-20_24x39_item_turbo-transport-belt.txt) · chocpaint | **20 → 20**<br>20 stacked turbo belts<br>≈ 4,800 items/s | — |
| <img src="images/chocpaint__oversize_20-128___24-24_44x23_Split-6_item_turbo-transport-belt.jpg" width="360"> | **24-24 [44x23] (Split-6, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___24-24_44x23_Split-6_item_turbo-transport-belt.txt) · chocpaint | **24 → 24**<br>24 stacked turbo belts<br>≈ 5,760 items/s | — |
| <img src="images/chocpaint__oversize_20-128___24-24_24x43_Inline_item_turbo-transport-belt.jpg" width="360"> | **24-24 [24x43] (Inline, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___24-24_24x43_Inline_item_turbo-transport-belt.txt) · chocpaint | **24 → 24**<br>24 stacked turbo belts<br>≈ 5,760 items/s | inline |
| <img src="images/raynquist__oversize_20-128___32-32_balancer_32x25.jpg" width="360"> | **32-32 balancer (32x25)**<br>[`bp`](blueprints/raynquist__oversize_20-128___32-32_balancer_32x25.txt) | **32 → 32**<br>32 stacked turbo belts<br>≈ 7,680 items/s | — |
| <img src="images/chocpaint__oversize_20-128___32-32_32x25_item_turbo-transport-belt.jpg" width="360"> | **32-32 [32x25] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___32-32_32x25_item_turbo-transport-belt.txt) · chocpaint | **32 → 32**<br>32 stacked turbo belts<br>≈ 7,680 items/s | — |
| <img src="images/chocpaint__oversize_20-128___32-32_32x47_Fractal_item_turbo-transport-belt.jpg" width="360"> | **32-32 [32x47] (Fractal, turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___32-32_32x47_Fractal_item_turbo-transport-belt.txt) · chocpaint | **32 → 32**<br>32 stacked turbo belts<br>≈ 7,680 items/s | fractal design |
| <img src="images/raynquist__oversize_20-128___64-64_balancer_64x46.jpg" width="360"> | **64-64 balancer (64x46)**<br>[`bp`](blueprints/raynquist__oversize_20-128___64-64_balancer_64x46.txt) | **64 → 64**<br>64 stacked turbo belts<br>≈ 15,360 items/s | — |
| <img src="images/chocpaint__oversize_20-128___64-64_64x54_item_turbo-transport-belt.jpg" width="360"> | **64-64 [64x54] (turbo-belt+)**<br>[`bp`](blueprints/chocpaint__oversize_20-128___64-64_64x54_item_turbo-transport-belt.txt) · chocpaint | **64 → 64**<br>64 stacked turbo belts<br>≈ 15,360 items/s | — |
| <img src="images/raynquist__oversize_20-128___128-128_balancer_128x72.jpg" width="360"> | **128-128 balancer (128x72)**<br>[`bp`](blueprints/raynquist__oversize_20-128___128-128_balancer_128x72.txt) | **128 → 128**<br>128 stacked turbo belts<br>≈ 30,720 items/s | — |

# lane balancers

Dedicated lane balancers: equalize the left/right lanes within belts (N in, N out).


| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__lane_balancers__1-1_TU_lane_balancer.jpg" width="360"> | **1-1 TU lane balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__1-1_TU_lane_balancer.txt) | **1 → 1**<br>1 stacked turbo belt<br>≈ 240 items/s | Lane balancers also balance both sides of each belt. Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are… |
| <img src="images/raynquist__lane_balancers__1-1_TU_lane_balancer_alt.jpg" width="360"> | **1-1 TU lane balancer (alt)**<br>[`bp`](blueprints/raynquist__lane_balancers__1-1_TU_lane_balancer_alt.txt) | **1 → 1**<br>1 stacked turbo belt<br>≈ 240 items/s | Lane balancers also balance both sides of each belt. Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are… |
| <img src="images/raynquist__lane_balancers__1-1_TU_lane_corner_balancer.jpg" width="360"> | **1-1 TU lane corner balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__1-1_TU_lane_corner_balancer.txt) | **1 → 1**<br>1 stacked turbo belt<br>≈ 240 items/s | Lane balancers also balance both sides of each belt. Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are… |
| <img src="images/chocpaint__lane_balancers__1-1_2x3_UT_Lane_virtual-signal_signal-alert_Corner.jpg" width="360"> | **1-1 [2x3] (UT, Lane ⚠, Corner)**<br>[`bp`](blueprints/chocpaint__lane_balancers__1-1_2x3_UT_Lane_virtual-signal_signal-alert_Corner.txt) · chocpaint | **1 → 1**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput<br>lane-balanced<br>output turns 90°<br>⚠ not fully balanced |
| <img src="images/chocpaint__lane_balancers__1-1_3x3_UT_Lane_virtual-signal_signal-alert_Straight.jpg" width="360"> | **1-1 [3x3] (UT, Lane ⚠, Straight)**<br>[`bp`](blueprints/chocpaint__lane_balancers__1-1_3x3_UT_Lane_virtual-signal_signal-alert_Straight.txt) · chocpaint | **1 → 1**<br>1 stacked turbo belt<br>≈ 240 items/s | unlimited throughput<br>lane-balanced<br>straight-through<br>⚠ not fully balanced |
| <img src="images/raynquist__lane_balancers__2-2_lane_balancer.jpg" width="360"> | **2-2 lane balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__2-2_lane_balancer.txt) | **2 → 2**<br>2 stacked turbo belts<br>≈ 480 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/raynquist__lane_balancers__2-2_lane_corner_balancer.jpg" width="360"> | **2-2 lane corner balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__2-2_lane_corner_balancer.txt) | **2 → 2**<br>2 stacked turbo belts<br>≈ 480 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/chocpaint__lane_balancers__2-2_2x12_Lane_Inline_virtual-signal_signal-radioactivity.jpg" width="360"> | **2-2 [2x12] (Lane, Inline,  ☢)**<br>[`bp`](blueprints/chocpaint__lane_balancers__2-2_2x12_Lane_Inline_virtual-signal_signal-radioactivity.txt) · chocpaint | **2 → 2**<br>2 stacked turbo belts<br>≈ 480 items/s | lane-balanced<br>inline<br>☢ residual items possible |
| <img src="images/raynquist__lane_balancers__3-3_lane_balancer.jpg" width="360"> | **3-3 lane balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__3-3_lane_balancer.txt) | **3 → 3**<br>3 stacked turbo belts<br>≈ 720 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/raynquist__lane_balancers__4-4_lane_balancer.jpg" width="360"> | **4-4 lane balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__4-4_lane_balancer.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/raynquist__lane_balancers__4-4_lane_balancer_alt.jpg" width="360"> | **4-4 lane balancer (alt)**<br>[`bp`](blueprints/raynquist__lane_balancers__4-4_lane_balancer_alt.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/raynquist__lane_balancers__4-4_lane_corner_balancer.jpg" width="360"> | **4-4 lane corner balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__4-4_lane_corner_balancer.txt) | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/chocpaint__lane_balancers__4-4_4x13_Lane_Inline_virtual-signal_signal-radioactivity.jpg" width="360"> | **4-4 [4x13] (Lane, Inline,  ☢)**<br>[`bp`](blueprints/chocpaint__lane_balancers__4-4_4x13_Lane_Inline_virtual-signal_signal-radioactivity.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | lane-balanced<br>inline<br>☢ residual items possible |
| <img src="images/chocpaint__lane_balancers__4-4_6x8_Lane_Straight_virtual-signal_signal-alert_virtual-signal_signal-radioactivity.jpg" width="360"> | **4-4 [6x8] (Lane, Straight,  ⚠ ☢)**<br>[`bp`](blueprints/chocpaint__lane_balancers__4-4_6x8_Lane_Straight_virtual-signal_signal-alert_virtual-signal_signal-radioactivity.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | lane-balanced<br>straight-through<br>⚠ not fully balanced<br>☢ residual items possible<br>Warning: Beware unconnected EW underground belts. |
| <img src="images/chocpaint__lane_balancers__4-4_8x18_UT_Lane.jpg" width="360"> | **4-4 [8x18] (UT, Lane)**<br>[`bp`](blueprints/chocpaint__lane_balancers__4-4_8x18_UT_Lane.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | unlimited throughput<br>lane-balanced |
| <img src="images/raynquist__lane_balancers__6-6_lane_balancer.jpg" width="360"> | **6-6 lane balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__6-6_lane_balancer.txt) | **6 → 6**<br>6 stacked turbo belts<br>≈ 1,440 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/chocpaint__lane_balancers__6-6_9x13_Lane.jpg" width="360"> | **6-6 [9x13] (Lane)**<br>[`bp`](blueprints/chocpaint__lane_balancers__6-6_9x13_Lane.txt) · chocpaint | **6 → 6**<br>6 stacked turbo belts<br>≈ 1,440 items/s | lane-balanced |
| <img src="images/raynquist__lane_balancers__8-8_lane_balancer.jpg" width="360"> | **8-8 lane balancer**<br>[`bp`](blueprints/raynquist__lane_balancers__8-8_lane_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Lane balancers also balance both sides of each belt. |
| <img src="images/chocpaint__lane_balancers__8-8_16x31_UT_Lane.jpg" width="360"> | **8-8 [16x31] (UT, Lane)**<br>[`bp`](blueprints/chocpaint__lane_balancers__8-8_16x31_UT_Lane.txt) · chocpaint | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | unlimited throughput<br>lane-balanced |
| <img src="images/chocpaint__lane_balancers__16-16_30x40_UT_Lane.jpg" width="360"> | **16-16 [30x40] (UT, Lane)**<br>[`bp`](blueprints/chocpaint__lane_balancers__16-16_30x40_UT_Lane.txt) · chocpaint | **16 → 16**<br>16 stacked turbo belts<br>≈ 3,840 items/s | unlimited throughput<br>lane-balanced |

# lane splitters

Split each lane of a belt onto its own belt (e.g. 2 belts in, 4 half-lane belts out).


| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/chocpaint__lane_splitters__2_2_4_4x8_Edge-Slim.jpg" width="360"> | **2+2=4 [4x8] (Edge-Slim)**<br>[`bp`](blueprints/chocpaint__lane_splitters__2_2_4_4x8_Edge-Slim.txt) · chocpaint | **2 → 2**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/chocpaint__lane_splitters__2_2_4_6x5_Edge-Wide.jpg" width="360"> | **2+2=4 [6x5] (Edge-Wide)**<br>[`bp`](blueprints/chocpaint__lane_splitters__2_2_4_6x5_Edge-Wide.txt) · chocpaint | **2 → 2**<br>2 stacked turbo belts<br>≈ 480 items/s | — |
| <img src="images/chocpaint__lane_splitters__4_4_8_10x7_Edge.jpg" width="360"> | **4+4=8 [10x7] (Edge)**<br>[`bp`](blueprints/chocpaint__lane_splitters__4_4_8_10x7_Edge.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | I/O on the edges |
| <img src="images/chocpaint__lane_splitters__4_4_8_8x16_Inline.jpg" width="360"> | **4+4=8 [8x16] (Inline)**<br>[`bp`](blueprints/chocpaint__lane_splitters__4_4_8_8x16_Inline.txt) · chocpaint | **4 → 4**<br>4 stacked turbo belts<br>≈ 960 items/s | inline |

# downgrades

*Originally cheaper yellow/red-belt variants of the designs above — upgraded to turbo like everything else here.*


| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__downgrades__4-8_TU_balancer.jpg" width="360"> | **4-8 TU balancer**<br>[`bp`](blueprints/raynquist__downgrades__4-8_TU_balancer.txt) | **4 → 8**<br>4 stacked turbo belts<br>≈ 960 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__downgrades__5-5_balancer.jpg" width="360"> | **5-5 balancer**<br>[`bp`](blueprints/raynquist__downgrades__5-5_balancer.txt) | **5 → 5**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__downgrades__5-6_balancer.jpg" width="360"> | **5-6 balancer**<br>[`bp`](blueprints/raynquist__downgrades__5-6_balancer.txt) | **5 → 6**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__downgrades__5-7_balancer.jpg" width="360"> | **5-7 balancer**<br>[`bp`](blueprints/raynquist__downgrades__5-7_balancer.txt) | **5 → 7**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__downgrades__5-8_balancer.jpg" width="360"> | **5-8 balancer**<br>[`bp`](blueprints/raynquist__downgrades__5-8_balancer.txt) | **5 → 8**<br>5 stacked turbo belts<br>≈ 1,200 items/s | — |
| <img src="images/raynquist__downgrades__6-4_TU_balancer.jpg" width="360"> | **6-4 TU balancer**<br>[`bp`](blueprints/raynquist__downgrades__6-4_TU_balancer.txt) | **6 → 4**<br>6 stacked turbo belts<br>≈ 1,440 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__downgrades__6-5_balancer.jpg" width="360"> | **6-5 balancer**<br>[`bp`](blueprints/raynquist__downgrades__6-5_balancer.txt) | **6 → 5**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__downgrades__6-6_balancer.jpg" width="360"> | **6-6 balancer**<br>[`bp`](blueprints/raynquist__downgrades__6-6_balancer.txt) | **6 → 6**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__downgrades__6-8_balancer.jpg" width="360"> | **6-8 balancer**<br>[`bp`](blueprints/raynquist__downgrades__6-8_balancer.txt) | **6 → 8**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__downgrades__6-9_balancer.jpg" width="360"> | **6-9 balancer**<br>[`bp`](blueprints/raynquist__downgrades__6-9_balancer.txt) | **6 → 9**<br>6 stacked turbo belts<br>≈ 1,440 items/s | — |
| <img src="images/raynquist__downgrades__7-5_balancer.jpg" width="360"> | **7-5 balancer**<br>[`bp`](blueprints/raynquist__downgrades__7-5_balancer.txt) | **7 → 5**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__downgrades__7-7_balancer.jpg" width="360"> | **7-7 balancer**<br>[`bp`](blueprints/raynquist__downgrades__7-7_balancer.txt) | **7 → 7**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__downgrades__7-8_balancer.jpg" width="360"> | **7-8 balancer**<br>[`bp`](blueprints/raynquist__downgrades__7-8_balancer.txt) | **7 → 8**<br>7 stacked turbo belts<br>≈ 1,680 items/s | — |
| <img src="images/raynquist__downgrades__8-4_TU_balancer.jpg" width="360"> | **8-4 TU balancer**<br>[`bp`](blueprints/raynquist__downgrades__8-4_TU_balancer.txt) | **8 → 4**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__downgrades__8-5_balancer.jpg" width="360"> | **8-5 balancer**<br>[`bp`](blueprints/raynquist__downgrades__8-5_balancer.txt) | **8 → 5**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__downgrades__8-7_balancer.jpg" width="360"> | **8-7 balancer**<br>[`bp`](blueprints/raynquist__downgrades__8-7_balancer.txt) | **8 → 7**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__downgrades__8-8_balancer.jpg" width="360"> | **8-8 balancer**<br>[`bp`](blueprints/raynquist__downgrades__8-8_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__downgrades__8-8_corner_balancer.jpg" width="360"> | **8-8 corner balancer**<br>[`bp`](blueprints/raynquist__downgrades__8-8_corner_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | — |
| <img src="images/raynquist__downgrades__8-8_TU_balancer.jpg" width="360"> | **8-8 TU balancer**<br>[`bp`](blueprints/raynquist__downgrades__8-8_TU_balancer.txt) | **8 → 8**<br>8 stacked turbo belts<br>≈ 1,920 items/s | Throughput-unlimited (TU) balancers always provide full throughput. Regular balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. |
| <img src="images/raynquist__downgrades__9-4_balancer.jpg" width="360"> | **9-4 balancer**<br>[`bp`](blueprints/raynquist__downgrades__9-4_balancer.txt) | **9 → 4**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__downgrades__9-6_balancer.jpg" width="360"> | **9-6 balancer**<br>[`bp`](blueprints/raynquist__downgrades__9-6_balancer.txt) | **9 → 6**<br>9 stacked turbo belts<br>≈ 2,160 items/s | — |
| <img src="images/raynquist__downgrades__16-16_balancer.jpg" width="360"> | **16-16 balancer**<br>[`bp`](blueprints/raynquist__downgrades__16-16_balancer.txt) | **16 → 16**<br>16 stacked turbo belts<br>≈ 3,840 items/s | — |

# FAQ

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__FAQ__What_s_with_the_item_deconstruction-planner_filter.jpg" width="360"> | **What's with the deconstruction planner filter?**<br>[`bp`](blueprints/raynquist__FAQ__What_s_with_the_item_deconstruction-planner_filter.txt) | — | It's to stop the splitter from outputting on that side because it'll sideload onto the underground in front of it otherwise. Setting the filter to deconstruction planner means only deconstruction planners can output on t… |
| <img src="images/raynquist__FAQ__Why_does_the_4-4_have_two_extra_splitters_at_the_end.jpg" width="360"> | **Why does the 4-4 have two extra splitters at the end?**<br>[`bp`](blueprints/raynquist__FAQ__Why_does_the_4-4_have_two_extra_splitters_at_the_end.txt) | — | It makes the 4-4 TU. Without them the 4-4 would still be a balancer, just not a TU one. signal 1 If you take two regular 4-4's signal 2 and combine them, you'd get a TU 4-4. signal 3 But two of the splitters are redundan… |
| <img src="images/raynquist__FAQ__What_does_TU_mean.jpg" width="360"> | **What does TU mean?**<br>[`bp`](blueprints/raynquist__FAQ__What_does_TU_mean.txt) | — | Throughput-unlimited (TU) balancers always provide full throughput. Regular n-n balancers are only guaranteed to provide full throughput when all inputs or all outputs are utilized. Regular n-m balancers are only guarant… |
| <img src="images/raynquist__FAQ__What_does_L_mean.jpg" width="360"> | **What does L mean?**<br>[`bp`](blueprints/raynquist__FAQ__What_does_L_mean.txt) | — | Lane (L) balancers, in addition to balancing belts, also balance the left sides of belts with the right sides. |
| <img src="images/raynquist__FAQ__Don_t_splitters_already_balance_lanes.jpg" width="360"> | **Don't splitters already balance lanes?**<br>[`bp`](blueprints/raynquist__FAQ__Don_t_splitters_already_balance_lanes.txt) | — | They do not. Splitters balance left lanes with left lanes (signal A with signal C), and right lanes with right lanes (signal B with signal D). As a result belt balancers also balance left and right lanes separately. |
| <img src="images/raynquist__FAQ__Why_not_just_use_a_splitter_then_sideload_the_2_belts_onto_1_belt_to_balance_lanes.jpg" width="360"> | **Why not just use a splitter then sideload the 2 belts onto 1 belt to balance lanes?**<br>[`bp`](blueprints/raynquist__FAQ__Why_not_just_use_a_splitter_then_sideload_the_2_belts_onto_1_belt_to_balance_lanes.txt) | — | You can use this if you just want output balancing, but if you want input balancing this does not work. Input balancing is only applicable when belts are backed up, and when belts are backed up the signal Left and signal… |
| <img src="images/raynquist__FAQ__Why_do_the_lane_balancers_only_balance_half_the_lanes.jpg" width="360"> | **Why do the lane balancers only balance half the lanes?**<br>[`bp`](blueprints/raynquist__FAQ__Why_do_the_lane_balancers_only_balance_half_the_lanes.txt) | — | They balances all lanes. The sideloading parts (signal 1) may resemble output lane balancers (signal 2), but because they sideload onto undergrounds instead of belts, they don't actually do any balancing. Their purpose i… |
| <img src="images/raynquist__FAQ__Isn_t_the_2-2_lane_balancer_TU.jpg" width="360"> | **Isn't the 2-2 lane balancer TU?**<br>[`bp`](blueprints/raynquist__FAQ__Isn_t_the_2-2_lane_balancer_TU.txt) | — | The 2-2 lane balancer is not TU, and is not labeled as such. To make a 2-2 TU lane balancer combine two of them like usual. |
| <img src="images/raynquist__FAQ__Why_is_the_balancer_not_mixing_the_items.jpg" width="360"> | **Why is the balancer not mixing the items?**<br>[`bp`](blueprints/raynquist__FAQ__Why_is_the_balancer_not_mixing_the_items.txt) | — | This is a behavior you can observe with just a 2-2 splitter. Splitters only care about the amount of items going through them. As long as the amount of items are correct, the splitter doesn't guarantee that it'll produce… |
| <img src="images/raynquist__FAQ__Why_don_t_you_take_the_4-4_TU_balancer_and_omit_one_input_and_or_output_to_make_a_smaller_balancer.jpg" width="360"> | **Why don't you take the 4-4 TU balancer and omit one input and/or output to make a smaller balancer?**<br>[`bp`](blueprints/raynquist__FAQ__Why_don_t_you_take_the_4-4_TU_balancer_and_omit_one_input_and_or_output_to_make_a_smaller_balancer.txt) | — | While it's true that a TU balancer guarantees full throughput regardless of how the inputs and outputs are utilized, it doesn't provide a similar guarantee for balance. The balance properties of TU balancers are the same… |
| <img src="images/raynquist__FAQ__Where_can_I_find_the_latest_version_of_this_book.jpg" width="360"> | **Where can I find the latest version of this book?**<br>[`bp`](blueprints/raynquist__FAQ__Where_can_I_find_the_latest_version_of_this_book.txt) | — | https://github.com/raynquist/balancer/blob/master/blueprints/balancer_book.txt |

## How do I make my own balancers?

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__How_do_I_make_my_own_balancers___Basic_balancing_theory.jpg" width="360"> | **Basic balancing theory**<br>[`bp`](blueprints/raynquist__How_do_I_make_my_own_balancers___Basic_balancing_theory.txt) | — | see: https://www.reddit.com/gallery/jqfhlu |
| <img src="images/raynquist__How_do_I_make_my_own_balancers___Basic_lane_balancing_theory.jpg" width="360"> | **Basic lane balancing theory**<br>[`bp`](blueprints/raynquist__How_do_I_make_my_own_balancers___Basic_lane_balancing_theory.txt) | — | see: https://www.reddit.com/gallery/jyxv5w |
| <img src="images/raynquist__How_do_I_make_my_own_balancers___Basic_TU_balancing_theory.jpg" width="360"> | **Basic TU balancing theory**<br>[`bp`](blueprints/raynquist__How_do_I_make_my_own_balancers___Basic_TU_balancing_theory.txt) | — | TU balancers are typically made by taking regular versions of the balancers and using two copies of them back-to-back. Recall that regular balancers guarantee full throughput if the inputs or outputs are fully utilized. … |
| <img src="images/raynquist__How_do_I_make_my_own_balancers___Basic_n-m_TU_balancing_theory.jpg" width="360"> | **Basic n-m TU balancing theory**<br>[`bp`](blueprints/raynquist__How_do_I_make_my_own_balancers___Basic_n-m_TU_balancing_theory.txt) | — | n-m TU balancers can be made by following the same basic theory as n-n TU balancers. They're typically made by connecting a regular n-m with a regular m-m, assuming m > n. If n > m then connect a regular n-n with a regul… |
| <img src="images/raynquist__How_do_I_make_my_own_balancers___Balancer_verifiers.jpg" width="360"> | **Balancer verifiers**<br>[`bp`](blueprints/raynquist__How_do_I_make_my_own_balancers___Balancer_verifiers.txt) | — | There are programs that can verify the correctness of balancers. The ones I know of are: github.com/d4rkc0d3r/FactorioSimulation/releases github.com/tzwaan/factorio_balancers/releases github.com/alegnani/verifactory/rele… |

### Advanced techniques

| Preview | Balancer | Moves (fully stacked) | Notes |
|---|---|---|---|
| <img src="images/raynquist__Advanced_techniques__Emergent_sub-balancer_substitution.jpg" width="360"> | **Emergent sub-balancer substitution**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Emergent_sub-balancer_substitution.txt) | — | "Unintentional" sub-balancers found in balancers can be replaced with equivalent sub-balancers. signal 1 E.g. if you take two 3-3s signal 2 and combine them into a 6-6, signal 3 you may find a new 4-4 (fast splitter) ins… |
| <img src="images/raynquist__Advanced_techniques__Sub-tree_merge.jpg" width="360"> | **Sub-tree merge**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Sub-tree_merge.txt) | — | signal 1 1-5 is typically constructed using two loopbacks. signal 2 The two loopbacks are usually from the same branch, but they don't have to be. signal 3 If we ignore one of the splitters, signal 4 the two loopback spl… |
| <img src="images/raynquist__Advanced_techniques__Loopback_substitution.jpg" width="360"> | **Loopback substitution**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Loopback_substitution.txt) | — | signal 1 E.g. Take the 1-5 from "Sub-tree merge". signal 2 Looking at the outputs, the three output splitters not only output the five outputs, but they also output one loopback. Because the loopback comes from an output… |
| <img src="images/raynquist__Advanced_techniques__Equal_belt_substitution.jpg" width="360"> | **Equal belt substitution**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Equal_belt_substitution.txt) | — | Equivalent belts in general are interchangeable, not just inputs/outputs. signal 1 E.g. take the 1-5 from "Loopback substitution". signal 2 The three output splitters are all 1-2, so their inputs (fast transport belt) ar… |
| <img src="images/raynquist__Advanced_techniques__Re-balance_substitution.jpg" width="360"> | **Re-balance substitution**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Re-balance_substitution.txt) | — | signal 1 A 1-9 can be made by combining four 1-3's. signal 2 Observe that eight of the outputs come from two internal belts (fast transport belt). signal 3 So we can just use a 2-8 instead. The 2-8 doesn't function exact… |
| <img src="images/raynquist__Advanced_techniques__Complete_the_square.jpg" width="360"> | **Complete the square**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Complete_the_square.txt) | — | signal 1 E.g. take the 1-5 from "Loopback substitution". signal 2 It naturally has four unused inputs (transport belt). Think of it as being fed four belts of emptiness. So each output belt has 1/5 belt of items and 4/5 … |
| <img src="images/raynquist__Advanced_techniques__Complete_the_square_cont..jpg" width="360"> | **Complete the square (cont.)**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Complete_the_square_cont..txt) | — | ABCDE only describes output balance, however because the 5-5 consists of entirely 2-2 splitters, if one side is balanced then the other side must also be balanced. This is also why only the 4-4 works. If you instead comb… |
| <img src="images/raynquist__Advanced_techniques__Complete_the_rectangle.jpg" width="360"> | **Complete the rectangle**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Complete_the_rectangle.txt) | — | signal 1 From "Sub-tree merge", we have this 3:2 ratio splitter. signal 2 If we feed the empty input with a belt, then all the emptiness would be filled, and the output becomes two full belts. signal 3 The rectangle can … |
| <img src="images/raynquist__Advanced_techniques__Sub-graph_substitution.jpg" width="360"> | **Sub-graph substitution**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Sub-graph_substitution.txt) | — | Sub-graphs don't need to be balancers to be subtituted. Any sub-graph can be subtituted with something that's equivalent in functionality. signal 1 A conventionally constructed 2-5 has a 3:2 ratio splitter (splitter, fro… |
| <img src="images/raynquist__Advanced_techniques__Deferred_loopback.jpg" width="360"> | **Deferred loopback**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Deferred_loopback.txt) | — | If a TU balancer is contructed by combining two plain balancers that have top level loopbacks (a 3-3 for example), those loopbacks can instead be done after the two balancers are combined. |
| <img src="images/raynquist__Advanced_techniques__Upsize_then_balance.jpg" width="360"> | **Upsize then balance**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Upsize_then_balance.txt) | — | n-m TU balancers are typically made by connecting regular n-m to a regular m-m. However in some cases it may be more efficient to multiply each of the n belts until there are a total of m belts, then balance them. For TU… |
| <img src="images/raynquist__Advanced_techniques__Input_priority_for_TU_1-n.jpg" width="360"> | **Input priority for TU 1-n**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Input_priority_for_TU_1-n.txt) | — | Intuitively one would think that 1-n balancers are all TU. However when loopbacks are involved the loopbacks can compete with inputs for throughput. This can be fixed by prioritizing the input over the loopback. Usually … |
| <img src="images/raynquist__Advanced_techniques__Custom_TU_solutions.jpg" width="360"> | **Custom TU solutions**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Custom_TU_solutions.txt) | — | see: https://www.reddit.com/r/factorio/comments/u4nwzj/33_tu_balancer_and_new_construction_method/ https://www.reddit.com/r/factorio/comments/v20w30/new_throughput_unlimited_balancers_details_in/ |
| <img src="images/raynquist__Advanced_techniques__Balancer_layout_generator.jpg" width="360"> | **Balancer layout generator**<br>[`bp`](blueprints/raynquist__Advanced_techniques__Balancer_layout_generator.txt) | — | Balancer layouts can be auto-generated using Factorio-SAT. https://github.com/R-O-C-K-E-T/Factorio-SAT https://www.reddit.com/r/factorio/comments/u7zv6d/balancer_book_update_spring_2022/i5hvmxw/ |

# helpful tools

In-game upgrade/deconstruction planner helpers.


*Contains 12 upgrade/deconstruction planners (in-game tools — not rendered).*
