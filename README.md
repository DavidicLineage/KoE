# KoE — The Key of English

A spiral parser for the Phoenician script family.

## What this is

Words in Phoenician-descended scripts (English, Hebrew, Greek, Arabic, and Phoenician itself) carry meaning not just through sequence but through a center-out-and-back alternation pattern over their letters. Each letter is a glyph with a role inherited from its Phoenician pictograph; each word is parsed by an invariant rule:

1. Bite the center (one glyph for odd-length words, two for even).
2. Take the outermost pair.
3. Take the next pair from nearest center.
4. Continue alternating outward and inward until the word is exhausted.

This produces a *torque profile* — a structured reading of the word's semantic load through the paired roles of its glyphs.

## Scope

The framework is calibrated within the Phoenician script family — the family that shares letters descended from the original 22 Phoenician pictographs. It has not been validated on unrelated alphabet families (logographic systems, abugidas, or non-Phoenician abjads), and would require fresh calibration there.

## Formal substrate

The spiral parse rule is a specific instance of a Median-Extremes Alternation (MEA) operation on ordered sequences. The combinatorial properties of MEA are formalized in:

> Carr, D. (2026). *Median-Extremes Alternation Permutations: Initial Structural Results.* arXiv:2603.16971.

In this formalization, the parse rule is the same operation that generates the MEA permutation family, applied to the letter-positions of a word rather than to the elements of [n].

## Contents

- `LICENSE` — Apache License 2.0
- (forthcoming) Glyph reference tables for English, Hebrew, Greek, Arabic, and Phoenician
- (forthcoming) Worked examples across scripts
- (forthcoming) Manuscript material from *Architect of Zion*, Chapter 1: Torque and Logos

## Status

Early-stage public archive. The framework has been developed privately over approximately 24 years; this repository exists to make it durably findable and forkable by anyone whose work intersects with it — comparative philology, cognitive linguistics of literacy, orthographic depth research, or adjacent fields.

## License

Apache License 2.0. See LICENSE for full terms. Use freely; attribution required per the license.

## Contact

davidiclineage@protonmail.com
