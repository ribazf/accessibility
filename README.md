# Accessibility Demo

A minimal before-and-after accessibility demo (plain HTML, CSS, minimal JavaScript) for team lunch-and-learn sessions.

## Pages

| Page | Purpose |
|------|--------|
| [accessibility-issues.html](accessibility-issues.html) | Intentionally includes 6 common issues; fails Lighthouse/BrowserStack/axe |
| [accessibility-fixed.html](accessibility-fixed.html) | Same content, fixed; passes accessibility checks |

## Issues covered

1. **Low color contrast** – light gray on white vs WCAG 2.2 AA–compliant contrast  
2. **Missing image description** – no `alt` vs meaningful `alt` text  
3. **Keyboard not supported** – clickable `div` vs proper `button`  
4. **No visible focus** – `outline: none` vs visible focus styles  
5. **Forms without labels/errors** – placeholder-only, vague “Error” vs labels and `aria-describedby`  
6. **Missing ARIA labels** – icon-only button without `aria-label` vs with `aria-label`  

## Hosting on GitLab

- Push this repo to GitLab.
- For **GitLab Pages**: enable Pages in **Settings → Pages** and use a static site (e.g. “plain HTML”). The root is the project root; open `index.html` or link to the two HTML files.
- Or open the HTML files directly from the repository in your browser.

No build step; no frameworks.
