---
name: make-it-beautiful
description: Improve the visual design and usability of an existing web interface while preserving behavior, accessibility, responsive layout, and project conventions. Use when asked to polish, refine, redesign, or make a website, page, or UI feel more professional.
---

# Make It Beautiful

Help the user make an existing interface feel clear, cohesive, and carefully designed—not merely decorated.

## Working agreement

- Treat the repository as the source of truth. Inspect its framework, components, styling approach, and project instructions before editing.
- Preserve current behavior, routes, data flow, and useful content unless the user asks for a change.
- Prefer a focused, coherent improvement over a broad rewrite.
- Do not add dependencies just to achieve a visual effect.
- Never claim you ran a test, opened a browser, or verified a viewport unless you actually did.
- If a missing detail could materially change the design, ask one concise question. Otherwise, make a sensible choice and explain it.

## Workflow

### 1. Inspect before changing

Review the relevant page, nearby components, styles, assets, and project conventions.

Identify:
- The page's main goal and primary action.
- Its current visual hierarchy.
- Inconsistent spacing, typography, alignment, or color.
- Mobile layout risks and potential overflow.
- Relevant interaction states and accessibility issues.
- Existing design tokens and reusable components.

Use browser or screenshot tools if available. If not, work from the source and state that visual verification was limited.

### 2. Prioritize

Rank improvements by user impact:

1. Structure and hierarchy.
2. Layout and spacing.
3. Typography and readability.
4. Color, contrast, and surfaces.
5. Component and interaction details.
6. Motion and decoration.

For substantial work, share a short plan before implementation.

### 3. Implement a cohesive design

- **Hierarchy:** Make the primary action clear and content easy to scan.
- **Spacing:** Use consistent rhythm and alignment.
- **Typography:** Establish an intentional type scale and comfortable reading widths.
- **Color:** Give backgrounds, surfaces, text, borders, and accents clear roles.
- **Contrast:** Prioritize readable text over fashionable colors.
- **Responsive behavior:** Check narrow widths, wrapping, touch targets, and overflow.
- **Interaction states:** Consider hover, focus-visible, active, disabled, loading, empty, success, and error states where relevant.
- **Accessibility:** Use semantic elements, labels, keyboard support, visible focus, appropriate contrast, and reduced-motion support.
- **Content first:** Remove visual noise instead of adding decoration that competes with the task.
- **Project consistency:** Reuse existing tokens and components wherever possible.

Avoid defaulting to generic gradients, excessive glass effects, piles of cards, oversized corners, unnecessary animations, or purposeless icons. Use these patterns only when they fit the product.

### 4. Verify

Use the project's existing tools where appropriate:

- Run relevant lint, type-check, test, or build commands.
- Review the diff for unrelated edits and accidental behavior changes.
- Check responsive behavior with available browser tools or tests.
- Check keyboard focus and interaction states when possible.

If a check cannot be run, say so plainly. Never report unperformed checks as passing.

### 5. Report back

Summarize:
- The meaningful changes made.
- Behavior preserved or changed.
- Checks actually run and their results.
- Remaining limitations or recommended follow-up.

Keep the report concise and specific.

## If the user asks for ideas only

Do not modify files unless asked. Offer a prioritized design direction grounded in the current project.

## Definition of done

The interface should be easier to scan, visually consistent, usable on small screens, accessible to the extent supported by the implementation, aligned with the product, and still behave like the existing app.
