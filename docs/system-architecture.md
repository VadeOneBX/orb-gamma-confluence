# System architecture (conceptual)

## What the artifact shows

**HOSTAGE STATUS** (main table) carries **GEX Regime**, **GEX Confidence**, **Allowed Plays**, **Flip Risk**, **Minutes Since Open**, **0DTE Gate**, **Score (NEG/POS)**, **Net / Mode**, and caption rows named on the overlay (including **Execution Mode** and **Rule**).

**SPY/QQQ index tiles** (optional, compact or multi-line) repeat **GEX Regime**, **ORB** status text, **VWAP** **Above** / **Below** (with **STR** where used), and session **change** copy—so **opening range structure** and **VWAP relationship** sit beside **GEX regime** without merging those axes.

## How the visible fields cohere

**GEX Regime**, **GEX Confidence**, **Score (NEG/POS)**, and **Net / Mode** are the table’s **confluence surface**: one **composite read** that draws, when needed, on **A-side** checkpoints (premarket skew, IV vs price, pin/expand) and **C-side** material (**Unusual Whales**-style toggles A1, FA1, B1, FB2, NF1, plus **composite ORB** holds/failed handling), under **Regime Mode** (MANUAL, AUTO, HYBRID).

## Opening range structure and VWAP on the chart

Tile **ORB** lines express **opening range structure** in dashboard vernacular (**ORB BUILD**, **ORB SET**, **ORB HOLDS**, **ORB FAILED**, **ORB FAIL?**, **TRY UP** / **TRY DN**, etc.). **VWAP relationship** appears on the same tiles and, when the relevant option is on, can condition how **ORB hold** status is drawn.

## Regime context

**GEX Regime** must be read with **session phase**, **RTH** tile visibility, and the active **Regime Mode** branch in mind (including **NF1** neutralizing the auto read). Those shifts are **context on the saved dashboard**, not a universal classification scheme.

## Fixed point

The thread treated **HOSTAGE STATUS** plus **SPY/QQQ** tiles as the **stable object**; other material in the file exists chiefly to **populate those readings**.

## Boundary

This note stops at **what is visible and how to read it archivally**.
