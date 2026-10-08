# Scouty documentation instructions

## Project

- This is the Mintlify documentation site for Scouty.
- Pages are MDX with YAML frontmatter. Site configuration lives in `docs.json`.
- The audience is an end user finding prospects, sending outreach, and managing meetings in Scouty.
- Treat the application code and tests as the source of truth. The application README is secondary and may be outdated.

## Terminology

- Use **Scouty** for the product.
- Use **project** for saved outreach work and **campaign** for a targeting strategy.
- Use the exact UI labels in bold, such as **Check matches**, **Rewrite**, and **Check connection**.
- Use **Booking link** for an external scheduling page. Use **Google Meet link** only for the join link created with a calendar event.
- Describe usage limits as Scouty limits unless the UI identifies a provider limit.

## Style

- Write in English, active voice, and second person.
- Keep sentences short and headings in sentence case.
- Explain the purpose, prerequisites, steps, expected result, and recovery path for each workflow.
- Prefer numbered steps for actions and tables for state definitions.
- Add links to related pages when a task continues elsewhere.
- Focus on the business outcome and the action the user takes.
- Explain a technical term only when the user needs it to complete a task, such as entering DNS records for a custom domain.

## Content boundaries

- Do not describe servers, databases, cookies, browser storage, caches, snapshots, provider requests, concurrency controls, or implementation architecture in end-user pages.
- Do not publish secrets, infrastructure configuration, internal endpoints, database details, or migration instructions.
- Do not promise fixed production quotas unless the configured entitlement has been verified.
- Do not invent a support email or support channel.
- Do not document features that are absent from the current application.
- Do not document removed **Save to project** or **Saved leads** controls. Say that company results are saved automatically.

## Validation

Run `mint validate`, `mint broken-links`, and `mint a11y`. Preview changed pages at desktop and mobile widths. Work on a branch because changes to the default branch may publish automatically.
