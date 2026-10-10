---
name: frontend-design-rules
description: Apply practical visual design principles when creating, reviewing, or improving frontend interfaces. Use when building UI, designing page layouts, choosing typography and colors, arranging components, or refining visual composition and hierarchy.
---

# Frontend Design Rules

## Purpose

Help coding agents create thoughtful, usable, and visually coherent frontend interfaces by applying relevant design principles to the task at hand.

The goal is **thoughtful design decisions, not identical designs**.

These rules are decision-making tools, not a universal template. Apply them according to the product, audience, content, brand, interaction requirements, and visual direction. Do not force every principle into every interface.

## Core Instructions

When creating or improving a frontend interface:

1. **Understand the context.** Consider the purpose of the page, target audience, content, brand identity, user goals, and technical constraints before making visual decisions.
2. **Choose relevant principles.** Read the rules that directly support the current task. Apply additional rules when they meaningfully improve the result.
3. **Use judgment, not rigid formulas.** Treat design ratios, grids, alignment patterns, and compositional techniques as flexible guidance rather than mandatory requirements.
4. **Create a clear visual hierarchy.** Make important content easy to discover without making every element compete for attention.
5. **Prioritize usability and accessibility.** Maintain readable typography, sufficient contrast, visible interaction states, logical reading order, keyboard accessibility, and responsive behavior.
6. **Respect the existing product.** When modifying an established interface, preserve its recognizable visual identity and existing interaction patterns unless the task calls for a redesign.
7. **Avoid arbitrary decoration.** Do not add gradients, excessive rounded cards, glassmorphism, shadows, animations, or other fashionable effects without a clear design purpose.
8. **Validate the result.** Review the interface at realistic viewport sizes and check whether the visual choices support the intended user experience.

## Available Design Rules

Read the relevant files in `skills/frontend-design-rules/rules/` before applying their principles.

### Hierarchy and emphasis

- `rules/visual-hierarchy.md` — Establish a clear order of importance among interface elements.
- `rules/focal-point.md` — Give the interface an intentional focal point suited to its context and reading patterns.
- `rules/isolation-effect.md` — Distinguish important elements selectively without making everything compete for attention.

### Color and typography

- `rules/color-60-30-10.md` — Use the 60/30/10 color distribution as a flexible starting point for balancing dominant, secondary, and accent colors.
- `rules/typography-readability.md` — Make text readable and establish a useful typographic hierarchy.

### Spacing and visual balance

- `rules/proximity.md` — Use spacing and grouping to communicate relationships between elements.
- `rules/anchor-effect.md` — Make edge alignment, cropping, and placement feel intentional.
- `rules/optical-overshoot.md` — Account for perceived visual balance when geometric equality does not look visually equal.

### Layout and composition

- `rules/modular-grids.md` — Use modular grids when they help organize content into a coherent structure.
- `rules/column-grids.md` — Use columns to organize content while preserving readability and responsive behavior.
- `rules/rule-of-thirds.md` — Consider the rule of thirds when it improves composition, especially for image-led or editorial layouts.

## Applying the Rules

For each design task:

1. Identify the main user goal and the most important content.
2. Select the few principles that best address the task.
3. Make design decisions that work together rather than applying rules independently.
4. Check for conflicts between visual techniques and usability requirements.
5. Review the result and adjust anything that feels confusing, unbalanced, inaccessible, or arbitrary.

Not every interface needs a prominent hero, an asymmetrical layout, an accent-heavy call to action, or a rule-of-thirds composition. A centered layout, restrained palette, dense data table, or minimal interface may be the better solution.

When multiple approaches are valid, choose the one that best serves the product and explain significant trade-offs when useful.

## Quality Standard

A successful interface should feel intentional rather than formulaic. Visual choices should support content, hierarchy, usability, and the identity of the product.

Do not optimize for novelty alone. Do not apply all available rules just because they exist. Use the principles that make the interface better.
