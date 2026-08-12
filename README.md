# CATCH
## Contrast · Accessible name · Text spacing · Color · Headings

CATCH is a lightweight accessibility companion tool designed to help testers inspect common issues on web pages. It runs as a bookmarklet or injected script and provides an interactive overlay for:

- Accessible name inspection
- Image and alt text review
- Heading structure validation
- Contrast and color guidance
- Text spacing and layout checks

## Included files

- `CATCH.js` — main script implementing the CATCH overlay and accessibility checks.
- `index.html` — landing page describing the bookmarklets and usage.
- `test_catch_comprehensive.html` — sample test page for verifying CATCH behavior.

## Usage

1. Open `index.html` in a browser.
2. Use the bookmarklet links or manually inject `CATCH.js` into the page you want to test.
3. Click the CATCH button to open the overlay and switch between tabs for Name, Images, Headings, and Tools.

## Notes

- The accessible name inspection is approximate and may not cover every edge case.
- CATCH is intended as a companion testing utility, not a full automated accessibility auditor.

## License

No license is included in this repository. Use and modify at your own discretion.
