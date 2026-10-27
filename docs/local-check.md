# Local check summary

- Theme: Vercel · Prism 0.1.1
- Manifest SHA-256: `2403389b5e1474a5f7e9b1200ec48594e565d1799ef3c46340a564bcbe88bee3`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 17.93:1, title 17.93:1, link 5.68:1, tag 5.68:1, code 16.01:1, mark 15.13:1, chosen 14.98:1.
  - Dark: body 17.94:1, title 17.94:1, link 5.04:1, tag 5.04:1, code 16.6:1, mark 16.67:1, chosen 16.54:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
