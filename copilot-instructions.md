# GitHub Copilot Custom Instructions for WordPress Development

## Project Overview
This repository follows WordPress Coding Standards for themes and plugins, focusing on clean, maintainable code and modern block-based development.

## Coding & Styling Guidelines
- Prefer native WordPress block patterns over custom JavaScript or external libraries.
- Use `theme.json` for color palettes, typography, spacing, and layout settings.
- Maintain accessibility: semantic HTML, ARIA roles, alt text, and correct heading hierarchy.
- Follow WordPress PHP coding standards (4‑spaces indentation, meaningful function names, secure escaping/sanitization).
- Use semantic CSS naming (BEM or utility-first), avoid inline styles, and optimize assets (SVGs, WebP/AVIF).

## Tools & Workflow Expectations
- Use GitHub Issues for tasks, feature branches, and Pull Requests for code review.
- Log time in Harvest via GitHub issue integration (if applicable).
- Code in VS Code with GitHub Copilot; `.instructions.md` and prompt templates guide Copilot.
- Use WordPress Studio for syncing local development to live WordPress.com sandbox sites.

## PR & Documentation Standards
- Reference relevant issue numbers in commit messages (e.g. `Closes #5`).
- Use clear, descriptive PR titles and include a summary of changes.
- Keep documentation up to date (README, learning journal, new patterns/templates).
- Write test cases using Playwright for accessible page validation.

## Learning & Prompt Assistance
- Copilot should help write code, but always add context (e.g. "Add a new Nav pattern using `theme.json` variables").
- Use prompt files in `.github/prompts/` for repetitive tasks (pattern generation, accessibility reviews).
- Guide junior devs to write reflection posts in Markdown and review weekly submissions logically.
