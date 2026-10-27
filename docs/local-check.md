# Local check summary

- Theme: VS Code Plus · Prism 0.1.1
- Manifest SHA-256: `b87b3754357b4a2d01ab859694eacbee75def39ff2a0df5967968b2e61014d3a`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 21:1, title 21:1, link 5.68:1, tag 9.42:1, code 18.93:1, mark 18.82:1, chosen 16.89:1.
  - Dark: body 11.25:1, title 11.25:1, link 8.26:1, tag 5.99:1, code 10.33:1, mark 6.18:1, chosen 8.89:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
