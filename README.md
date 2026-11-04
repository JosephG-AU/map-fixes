# Enshrouded map usability review

A structured review of https://gameguides101.com/enshrouded-map/, performed on 4 November 2026.

The review covers **50 interaction scenarios by one automated reviewer**, with desktop and mobile viewport checks. It is not a study involving 50 participants, and this repository contains review evidence rather than implemented map fixes.

- [Full HTML report](ux-review-enshrouded/review.html) — download this repository and open the report locally to view the formatted report with screenshots.
- [50-interaction evidence log](ux-review-enshrouded/interactions.json)
- [Screenshots and test exports](ux-review-enshrouded/)

## Main findings

Strengths: broad map functionality, relevant resource search, flexible display controls, region analysis, persistent notes and pins, working progress exports/imports, and shared map views.

Priorities:

1. Give the map more space on mobile and move filters into a drawer.
2. Reduce default icon and label clutter.
3. Improve duplicate and unmapped quest presentation and player-facing names.
4. Make map workspaces easier to discover.
5. Remove test wording and explain coverage limits near results.

## Scope and limitations

Chrome desktop (1440 x 1000) and phone viewport (390 x 844), including a fresh touch-enabled context. The report describes the verification depth and limitations of each area. Real-device gestures, comprehensive accessibility, every item/subfilter, and game-world data accuracy were not validated.

JSON backups and the note export contain isolated test data, including the test pin named `UX test base`. No website source code or live server records were changed.

## Navigation design concepts

Three AI-generated visual alternatives using the existing map as a reference. These are design mockups, not implemented or tested navigation changes.

- [Download all three images as a ZIP](ux-review-enshrouded/enshrouded-navigation-concepts.zip)
- [Option 1: Grouped sidebar (recommended)](ux-review-enshrouded/navigation-concepts/01-grouped-sidebar.png)
- [Option 2: Horizontal menu](ux-review-enshrouded/navigation-concepts/02-horizontal-menu.png)
- [Option 3: Compact navigation rail](ux-review-enshrouded/navigation-concepts/03-compact-navigation-rail.png)
