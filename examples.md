# Worked Examples

Five examples demonstrating the spiral parser across cases. Each example walks through the parse step-by-step: word, letter positions, MEA permutation order, glyph roles, torque profile.

The parse rule is invariant across all cases. Only the glyph definitions and reading direction change between scripts.

---

## LOGOS

Five letters, odd length, single clutch.

```
Position:  1  2  3  4  5
Letter:    L  O  G  O  S
```

**MEA order:** 3, 1, 5, 2, 4 → G, L, S, O, O

**Spiral gears:**

1. **G** (center, clutch): Effort
2. **L + S** (outermost rails): Continuance + Redirect
3. **O + O** (next pair): Whole cycle + Whole cycle

**Torque profile:** Effort, redirected continuance, doubled whole cycles.

LOGOS reads as effort harnessed into polarized continuance, smoothed by reinforced cyclic closure. The word that names the gearbox embodies the gearbox.

---

## PARADOX

Seven letters, odd length, single clutch. The doubled A produces recursive torque.

```
Position:  1  2  3  4  5  6  7
Letter:    P  A  R  A  D  O  X
```

**MEA order:** 4, 1, 7, 2, 6, 3, 5 → A, P, X, A, O, R, D

**Spiral gears:**

1. **A** (center, clutch): Vehicle
2. **P + X** (outermost rails): Potential + Decision
3. **A + O** (next pair): Vehicle + Whole cycle
4. **R + D** (innermost pair): Result + Broken cycle

**Torque profile:** Vehicle, potential at decision, vehicle as whole cycle, result delivered into broken cycle.

The doubled A appears at two different gears, paired with different partners at each. The clutch A is the bare carrier; the inner-pair A is the carrier-as-completion. The torque between these two appearances of the same letter is what makes paradox paradoxical: the vehicle is both the engagement point and the recursive return.

---

## PARADE

Six letters, even length, dual clutch. Control case for PARADOX — same doubled A, different partner glyphs.

```
Position:  1  2  3  4  5  6
Letter:    P  A  R  A  D  E
```

**MEA order:** 3, 4, 1, 6, 2, 5 → R, A, P, E, A, D

**Spiral gears:**

1. **R + A** (center axis, dual clutch): Result + Vehicle
2. **P + E** (outermost rails): Potential + Measure
3. **A + D** (next pair): Vehicle + Broken cycle

**Torque profile:** Result delivered on a vehicle, measured potential, vehicle into broken cycle.

PARADE has the same doubled A as PARADOX, but neither A pairs with whole cycle. The clutch A pairs with R (delivery); the inner-pair A pairs with D (dismount). A parade carries-and-ends; a paradox carries-and-recurses. The framework distinguishes the two words by partner topology, not by surface letter overlap.

---

## PARA

Four letters, even length, dual clutch. The Greek prefix.

```
Position:  1  2  3  4
Letter:    P  A  R  A
```

**MEA order:** 2, 3, 1, 4 → A, R, P, A

**Spiral gears:**

1. **A + R** (center axis, dual clutch): Vehicle + Result
2. **P + A** (outermost rails): Potential + Vehicle

**Torque profile:** Vehicle's result, as potential vehicle.

The prefix *para-* in Greek marks its noun as an adjacent or parallel carrier (parallel, paramedic, paragraph, paradox). The spiral parse of the four letters reads as *vehicle's result, as potential vehicle* — a delivery that is itself another carrier in potential. The function of the preposition is recoverable from the spiral parse of its glyphs.

---

## THREE / שלשה / ΤΡΙΑ

Cross-script comparison of the cardinal three. The parse rule is invariant; the glyph tables and reading directions differ. The torque profiles converge on the structure of three but diverge in ways that track etymological differences between Indo-European and Semitic language families.

### English: T-H-R-E-E

Five letters, odd, single clutch.

**MEA order:** 3, 1, 5, 2, 4 → R, T, E, H, E

**Spiral gears:**

1. **R** (clutch): Result
2. **T + E** (outer rails): Sacrifice + Measure
3. **H + E** (inner pair): Union + Measure

**Torque profile:** Result, sacrifice measured, union measured.

### Hebrew: ש-ל-ש (Shloshah, masculine citation form)

Three letters, odd, single clutch. Read right-to-left.

**MEA order:** 2, 1, 3 → ל, ש, ש

**Spiral gears:**

1. **Lamed** (clutch): Teach / Toward
2. **Shin + Shin** (outer rails): Press / Consume + Press / Consume

**Torque profile:** Directional teaching, doubled consumption.

### Greek: Τ-Ρ-Ι-Α (Tria)

Four letters, even, dual clutch.

**MEA order:** 2, 3, 1, 4 → Ρ, Ι, Τ, Α

**Spiral gears:**

1. **Ρ + Ι** (dual clutch): Head/First + Work/Deed
2. **Τ + Α** (outer rails): Mark/Covenant + Strength/Leader

**Torque profile:** First deed, marked under covenant by the leader.

### Cross-script note

The English and Greek parses center on action-glyphs (Result; Head-First + Work-Deed). The Hebrew parse centers on a directional/instructional glyph (Teach/Toward). This tracks a real etymological divergence: Indo-European *tréyes* emphasizes the count and the third position; Semitic *šlš* emphasizes the iterative-instructional sense (cf. *shilshom*, "three days ago"; *meshulash*, "triangulated"). The framework reads the same cardinal number through different semantic foci consistent with the host language family.

---

## Method note

These parses are produced by applying the MEA permutation of [n] (where n is the word length) to the letter positions of the word, then reading off the role-pairs from the relevant glyph table per script. The MEA permutation family is formalized in arXiv:2603.16971. The glyph tables are in the root of this repository (TableRound, TableHex, TableSquare, TableSeptagon, TableTriangle).

The framework's claim is that the resulting torque profiles capture meaningful semantic structure. The claim is empirical and falsifiable: if the parses produce arbitrary or contradictory readings across cases, the framework fails. The examples here are offered as positive instances; readers are invited to test the framework on their own cases.
