# GoreeCloud Logo

Official GoreeCloud platform logo, brand marks, and canonical visual-identity assets.

## Status

**Official platform symbol:** Unified Clean — Blue  
**Canonical vector source:** `official/goreecloud-logo.svg`  
**Design language:** Glaze UI  
**Platform:** GoreeCloud

The canonical SVG is the source of truth. Raster icons, favicons, launcher artwork, social avatars, and other production derivatives must be generated from that approved vector source rather than independently redrawn.

## Repository structure

- `official/` — approved canonical artwork and official derivatives.
- `concepts/` — exploratory artwork retained for design history; not approved for production use.
- `BRAND.md` — identity meaning, usage, geometry, color, and brand rules.
- `PRODUCTION-ASSETS.md` — production export matrix and regeneration requirements.

## Core identity rule

The GoreeCloud symbol must remain recognizable as the same mark across web, mobile, desktop, documentation, repositories, and social profiles. Platform packaging may adapt canvas size, safe area, corner treatment, and required icon metadata, but it must not redesign the symbol geometry.

## Production workflow

1. Modify the canonical SVG only through an approved identity revision.
2. Validate the mark at full size and small icon sizes.
3. Regenerate production derivatives from the SVG.
4. Validate dimensions, transparency/background behavior, cropping, and file integrity.
5. Update identity documentation whenever the canonical artwork or its usage contract changes.

## Product integration

GoreeCloud applications and services should consume approved shared artwork rather than maintaining visually divergent copies. Product-specific icons may establish their own approved identities where required by the GoreeCloud visual-identity standard, while the GoreeCloud platform symbol remains the parent platform mark.

## Governance

This repository is the authoritative source-control location for the GoreeCloud platform visual identity. Experimental concepts are never production assets merely because they exist in this repository.

See `BRAND.md` and `PRODUCTION-ASSETS.md` before integrating or exporting the artwork.
