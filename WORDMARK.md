# GoreeCloud — Deep Cloud Wordmark Specification

## Status

I selected **Two Tone — Deep Cloud** as the GoreeCloud wordmark direction on August 19, 2026. This document defines the production requirements that must be satisfied before the wordmark is promoted to canonical official artwork.

The already-approved GoreeCloud platform symbol remains **Unified Clean — Blue** in `official/goreecloud-logo.svg`. Wordmark production must not alter that symbol.

## Selected visual hierarchy

The full-color wordmark uses two restrained text roles:

- `Goree` — dark neutral;
- `Cloud` — GoreeCloud Deep Blue `#174EA6`.

The distinction is intentionally typographic and chromatic rather than illustrative. I do not insert a space, separator, icon, cloud pictogram, gradient, outline, glow, or other decorative element between `Goree` and `Cloud`.

## Typography requirements

The final wordmark must use a legally distributable, open-source type foundation or custom vector lettering derived from one. The repository must not depend on a proprietary system font to reproduce canonical artwork.

Before approval, I require:

- stable letterforms across operating systems;
- deterministic vector output;
- optical kerning of the complete `GoreeCloud` name;
- careful treatment of the `eC` transition;
- sufficient counters and apertures at small sizes;
- a weight that visually balances the Unified Clean symbol without overpowering it;
- no synthetic font stretching or skewing.

Once finalized, the canonical SVG lockups should convert the lettering to vector paths so rendering does not depend on a locally installed font. The source typography and license must still be documented for maintainability.

## Horizontal lockup

The horizontal lockup is the preferred full identity where adequate width is available.

The approved symbol appears to the left of the wordmark. The wordmark is vertically aligned optically with the symbol rather than positioned solely by font metrics. The gap must remain visually generous enough that the symbol and name read as two coordinated identity components rather than one fused drawing.

I do not place the wordmark inside the symbol or allow the text to overlap the symbol's clear area.

## Stacked lockup

The stacked lockup is intended for narrower or more centered compositions. The approved symbol appears above the wordmark and remains visually dominant enough to preserve recognition.

The stacked arrangement may change spacing and relative presentation scale, but it must not change the symbol geometry or the `Goree` / `Cloud` hierarchy.

## Light presentation

On the approved light field or another validated light background:

- the platform symbol retains Primary Blue `#3B82F6` and Deep Blue `#174EA6`;
- `Goree` uses the approved dark-neutral production value established during finalization;
- `Cloud` uses Deep Blue `#174EA6`.

## Dark presentation

A dark-surface lockup may use a light/reversed treatment for `Goree` and a validated lighter blue treatment for `Cloud` where necessary for contrast. This is an accessibility/presentation derivative, not a change to the primary Deep Cloud identity hierarchy.

The exact dark-background colors must be documented in the canonical asset set before production use.

## Monochrome presentation

When reproduction does not permit the two-tone identity, an approved monochrome lockup may render the complete symbol and wordmark in a single validated color. Monochrome is a constrained-production derivative and must not replace the normal Deep Cloud presentation where full color is available.

## Clear space

Lockups require clear space around the complete composition, not merely around the symbol. No text, border, icon, photograph edge, or interface ornament should visually crowd the identity.

The final production SVGs must document a measurable clear-space unit derived from the approved geometry.

## Minimum size

The symbol-only identity remains preferred at sizes where the wordmark can no longer reproduce clearly. The final lockup package must establish tested minimum widths for horizontal and stacked arrangements after the typography has been converted to deterministic vector geometry.

## Canonical files planned

Production finalization should establish, at minimum:

- `official/goreecloud-wordmark.svg` — wordmark-only Deep Cloud artwork;
- `official/goreecloud-lockup-horizontal.svg` — primary symbol + wordmark lockup;
- `official/goreecloud-lockup-stacked.svg` — stacked lockup;
- corresponding reversed and monochrome derivatives where required.

These files must not be created as canonical artwork until the final vector typography and spacing have been visually validated.

## Relationship to Glaze UI

Glaze UI may provide surrounding layout, surface, depth, animation, or interaction treatment. It must not distort, recolor arbitrarily, animate individual logo components independently, or apply decorative effects that change the canonical GoreeCloud identity.

## Governance

The Deep Cloud wordmark is a selected identity direction, not permission for individual applications or repositories to recreate the text treatment independently. Once canonical lockups exist, GoreeCloud surfaces should consume those approved shared assets.

Any future material change to the `Goree` / `Cloud` hierarchy, wordmark letterforms, approved colors, or symbol relationship requires an explicit identity revision and corresponding documentation update.
