# Constraint design

## Role of constraints

**Constraints**—thresholds, filters, inclusion rules, and gating logic—function here as **design variables**. They carve the raw field into **emphasis patterns**: what counts as salient, what is suppressed, and what remains visible only in drill-down.

They are **not** documented as **validated edges**. A constraint may have been **motivated** by empirical observation in a historical window; in this artifact it is preserved as a **parameter of the dashboard’s geometry**, not as a proof of future performance or risk control.

## Design space, not boundary proofs

Each constraint implies a **family** of dashboards: loosen the gate, and more events surface; tighten it, and the narrative simplifies at the cost of breadth. The research treated that tradeoff as **central**. The preserved work is therefore best read as a **point in a design space**, with neighboring points left unexplored or deliberately discarded.

## Interaction with confluence

Confluence scoring sits **downstream** of constraints. Constraints determine **which observations enter** the composite and **how conflicts are resolved** when signals disagree. That ordering matters: confluence is **not independent** of the constraint sheet; it is **conditional** on it.

Readers should avoid interpreting any confluence state as **intrinsic** to the market. It is **intrinsic to the chosen constraint set** applied to a historical record.

## Regime and constraints

Some constraints may be **regime-aware** in intent: different gates for different volatility or liquidity contexts. Even then, the regime partition is a **modeling choice**. It organizes interpretation; it does not close the question of what regime the **current** environment represents.

## Exclusions

This document does not prescribe implementation details, execution policies, broker rules, or automation. It addresses **why constraints existed in the research** and **how to read them**—as levers in a composed view—not as operational mandates.
