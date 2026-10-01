# Frontend Design Rules

Build production-quality interfaces, not generic AI mockups.

## Visual Quality

* Every UI element must look intentional, polished, and professionally designed.
* Avoid generic "AI website" patterns, excessive rounded cards, unnecessary gradients, random glassmorphism, and repetitive layouts.
* Use strong visual hierarchy, deliberate spacing, typography, alignment, proportions, and whitespace.
* Do not add decoration just to fill empty space.
* Prefer a distinctive, coherent visual identity over default/template styling.

## Icons & Graphics

* NEVER use emojis as UI icons.
* NEVER use Unicode characters as substitute icons.
* Use Lucide or another consistent SVG icon library.
* Use custom SVGs when an icon needs to be unique.
* Inspect existing assets before creating replacements.
* If the design requires artwork, illustrations, characters, textures, or complex graphics, use actual image/SVG assets instead of fake placeholders.
* Never ship placeholder graphics in the finished UI.

## Design System

* Establish consistent colors, typography, spacing, border radii, shadows, and icon sizing.
* Reuse components and design tokens instead of styling every element independently.
* Keep the entire application visually consistent.
* Do not turn every piece of content into a card.

## Layout & UX

* Design desktop, tablet, and mobile intentionally rather than simply shrinking desktop.
* Navigation must have proper active, hover, and responsive states.
* Buttons, inputs, cards, menus, and other controls must have polished interaction states.
* Use animation sparingly and purposefully for feedback and transitions.

## Implementation

* Preserve existing functionality unless explicitly asked to change it.
* Inspect the existing project and assets before making design decisions.
* Prefer clean, maintainable components over duplicated code.
* Do not introduce unnecessary dependencies.

## Before Finishing

Perform a visual quality pass.

Look specifically for:

* emoji or fake icons
* placeholder graphics
* inconsistent spacing
* weak typography
* generic layouts
* inconsistent components
* poor responsive behavior
* unnecessary decoration

Fix these issues directly before considering the task complete.
