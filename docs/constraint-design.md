# Constraint design

## What shapes the visible read

Named groups in **`GEX_Hostage_Dashboard.pine.txt`** steer **HOSTAGE STATUS** and **SPY/QQQ** tiles: **ORB Context** (opening window, **ORB Hold** confirmation, optional **VWAP alignment** on holds), **session**, **GEX Hostage (Manual)**, **Unusual Whales (Manual Toggles)**, **Display**, **Index Tiles** (positions, stacking, **RTH** hide, compact mode), and **Regime Mode**. They are **design choices** on the chart: they change **which ORB wording and regime labels appear**, not off-chart “edges.”

## ORB validity and the C-side read

**Composite holds** and **composite failed** are **not double-counted** toward **C-side** scoring when both would fire—conflicting ORB headlines cannot **both** increment the same side. That convention is part of the **artifact’s scoring posture**, not a market theorem.

## One cut among neighbors

Combinations such as **VWAP alignment** on holds or MANUAL vs AUTO vs HYBRID imply other dashboards the file could have been; this repository holds **one preserved version**.

## Confluence surface dependence

**A-side** checkpoints and **C-side** toggles meet in **Score (NEG/POS)** and **Net / Mode**; **GEX Regime** / **GEX Confidence** reflect that meeting under **Regime Mode**. The **confluence surface** is always **bound to those inputs**.

## Regime context

**NF1** and related toggles show how **regime context** can **flatten or soften** what the auto branch would print. Treat that as **behavior recorded in the artifact**, not guidance outside it.

## Scope

Stays with the **preserved dashboard**; not a memo for anything beyond it.
