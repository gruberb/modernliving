# Changelog

All notable changes to the 1-25 Treehouse Lane listing site are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project uses [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2026-06-21

Hero and layout refinements following the initial overhaul.

### Added
- Full-bleed photo header with the title overlaid and a gradient scrim for
  legibility. The image is a single, well-commented swap point for a future
  interior/exterior photo.
- Floating spec card (Price, Bedrooms, Bathrooms, Home size, Shared land) with
  line icons, kept to a single row at every width via fluid `clamp()` scaling.
- Mobile contact bar now stays hidden over the hero and slides up only after
  the hero (which carries its own call/email buttons) scrolls out of view.

### Changed
- Section headers now stack the supporting line as a deck beneath the headline
  instead of floating it in a second column.
- Reworked the daily-life section into a balanced two-column block (heading and
  deck on the left, body copy on the right).
- Tightened vertical rhythm: reduced section padding and hero spacing, and
  loosened the oversized headline line-height so the lines no longer collide.

### Fixed
- Brochure photo strip and stats now collapse on small screens instead of
  cropping into thin vertical slivers.
- Removed stray default paragraph margins that were knocking supporting text
  out of alignment.

## [1.0.0] - 2026-06-20

Full visual overhaul of the listing site and printable brochure.

### Changed
- Reworked the visual identity from the cream/serif/terracotta default to a
  deep twilight-indigo ground with peach and butter-cream accents.
- Replaced the Playfair Display + Inter pairing with Anton (condensed display)
  and Hanken Grotesk (heads and body) across `index.html` and `brochure.html`.
- Restructured the homepage as a chaptered narrative (the home, the village,
  the place) with editorial image/text blocks for the shared spaces.
- Rebuilt the shared-spaces gallery as a 4x2 grid with a featured tile and
  expand-to-lightbox affordances on every photo.
- Reworked the apartment "coming soon" section into an honest invitation to
  request a showing or video walk-through rather than empty placeholder tiles.
- Aligned the brochure to the new identity and tuned it for clean PDF sharing.
- Updated the favicon to a peach-on-indigo tree-and-home mark.

### Added
- Scroll-triggered reveal animations, gated behind `prefers-reduced-motion`.
- Keyboard access to the lightbox from the hero and community image tiles.

### Fixed
- Unified the owner-contact copy so the calls to action no longer mix
  "the owners" with "Emily & Bastian".
- Hero image tiles now fill their cards edge to edge with no background gap,
  and hold up at tablet and mobile widths.
