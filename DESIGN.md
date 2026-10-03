# Design direction

<!-- impeccable:design-schema 1 -->

## World

The page uses an authored, playful editorial language: hot cherry, butter yellow, soft blue, paper, and ink. The visual metaphor is a small independent magazine that moves, folds, and gets a little loud when it needs to.

## Typography

Bricolage Grotesque provides the elastic, slightly offbeat voice for display and body copy. DM Mono is reserved for metadata, wayfinding, and small labels so it functions as measurement rather than costume.

## Composition

The first chapter is a 720vh scroll-scrubbed film: a sticky viewport, oversized words, changing color, and a growing sun. Later chapters deliberately change rhythm: a paper card peeks through pink, a full-bleed framed image field, shadowed shelf objects, and a wide marquee menu.

## Color

- Paper: `#f7f3ed` for the primary reading surface.
- Ink: `#17151a` for high-contrast text and structure.
- Cherry: `#ed4b35` for action and emphasis.
- Yellow: `#f6cf47` for energy and wayfinding.
- Blue: `#69a5e8` for the image and contact chapters.

## Interaction

The film scrubs by real scroll position, with distinct words, counters, and scale changes. Shelf objects lift with believable drop shadows, and the menu section uses an oversized marquee for a more impactful scroll beat. Mobile navigation is explicit and keyboard accessible. Reduced-motion users receive the same content without animated transitions.

## Responsive rules

The desktop page uses broad, art-directed chapters. At narrow widths, navigation becomes a disclosure, the film shortens while preserving the scrub interaction, the shelf stacks into a single column, and the marquee remains oversized without forcing horizontal scrolling.
