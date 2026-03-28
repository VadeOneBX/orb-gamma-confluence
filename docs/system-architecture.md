# System architecture (conceptual)

## Layered view

The dashboard can be read as a **small stack of intentions**, not as a deployment diagram.

1. **Representation layer**  
   Canonical charts, tables, and annotations arrange raw and derived quantities so they can be scanned in one sitting. Layout encodes priority: what must be visible first, what is secondary, what is diagnostic rather than primary.

2. **Synthesis layer**  
   Derived fields combine inputs into summaries—often labeled as confluence or agreement-style constructs. This layer is where **multiple signals are folded into fewer states** for visual economy.

3. **Parameter layer**  
   Constraints, windows, and classification rules sit **behind** the synthesis layer. They are **explicit levers**: changing them changes what the dashboard emphasizes without necessarily changing the underlying data source semantics.

There is no claim here that these layers map one-to-one to a particular technology stack. The architecture is **logical**: it describes how the preserved dashboard **thinks**, not how it was hosted or executed.

## Dashboard as the fixed point

Across iterations of the research, the dashboard remained the **stable object**. Experiments in scoring or constraint tuning were judged by whether they **clarified or obscured** that surface. The narrative therefore treats the dashboard as the **integration boundary**: the place where design decisions become visible and debatable.

## Data and environment (non-operational)

The work assumed **historical** data and **offline** interpretation. The architecture does not prescribe how data enters the system today; it describes **what classes of information** the dashboard was built to hold in relation—opening structure, gamma-related constructs, and confluence-style composites—without binding to a provider or pipeline.

## Regime in the architecture

Regime appears as **conditional interpretation**: the same composite may read differently when volatility, session phase, or microstructure context shifts. Architecturally, regime is **metadata for reading**, not a separate trading engine. It informs **how** to narrate a panel, not **what** must be executed.

## Boundary

This document stops at **conceptual structure**. It does not specify execution paths, connectivity, automation, or deployment. Those concerns were outside the preserved design story.
