# Add a "Docs" link to the main navigation

Add a "Docs" link to the top navigation / sidebar of the signed-in
Trigger.dev UI that opens https://trigger.dev/docs in a new tab.

## How to reach the app

Trigger.dev runs on http://localhost:8030. First-time use requires
signing up a new account (magic link flow — in the self-host stack,
the magic link URL is printed to the webapp container logs).

## Acceptance

- A "Docs" link is visible in the main nav on any signed-in page.
- Clicking it opens https://trigger.dev/docs in a new tab
  (target=_blank, rel=noopener).
- No other nav items are moved or removed.
