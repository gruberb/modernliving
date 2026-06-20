# Changelog

All notable changes to the 1-25 Treehouse Lane listing site are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project uses [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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
