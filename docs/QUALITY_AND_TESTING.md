# Portfolio QA and Maintenance Guide

The portfolio is a static HTML-oriented site with `index.html` as its main entry point. Confirm current assets and links in the source before describing interactive or deployed functionality.

## Run locally

Clone the repository and open the root `index.html` in a modern browser:

```bash
git clone https://github.com/kandisaikishore/portfolio.git
cd portfolio
```

## Content and link validation

- Verify every project link points to the intended source repository.
- Distinguish source-code links from verified live demos.
- Do not claim a deployment exists unless its URL has been opened and checked.
- Ensure contact links use the intended protocol and contain no placeholder values.
- Check that page titles, language metadata, image alt text, and heading hierarchy are meaningful.

## Accessibility and responsive checks

Test keyboard-only navigation, visible focus, link names, text contrast, and zoom behavior. Check mobile, tablet, and desktop widths. Avoid communicating important information by color alone and ensure images have useful alternative text.

## Automated checks

Use the commands documented in `QA_EXECUTION.md` and any scripts present in the repository. Add link/asset checks where possible. If checks are manual, record the browser, viewport, steps, and result instead of claiming an automated pass.

## Pull-request checklist

- [ ] Verify changed links and local assets.
- [ ] Check accessibility and responsive behavior for changed sections.
- [ ] Keep personal contact details accurate and intentional.
- [ ] Do not include private information or unverified deployment claims.
- [ ] Record the checks performed and any limitations.
