# Sample credit reports (dummy data)

```
index.html      Landing page linking to both reports
report-1.html   Report for "Jordan A. Rivera" (fictional)
report-2.html   Report for "Casey M. Lin" (fictional)
css/report.css  Shared styles (light, Udemy-style palette, Montserrat); colors and fonts are variables at the top
assets/logo.svg Placeholder logo; replace with your own file, same name
```

Open either HTML file in any browser. No build step, no JavaScript, no libraries.

## Updating content
- Every section starts with an HTML comment that says what to edit.
- **Scores:** edit or copy a `.score` block.
- **Personal info:** add or remove `<dt>`/`<dd>` pairs.
- **Trade lines:** copy one `<article class="tradeline">`, paste it, and change values. Status tag classes: `good`, `warn`, `bad`.
- **Inquiries / summary rows:** copy a `<tr>` and edit.
- **Embedding:** copy a whole `<section>` and include `css/report.css` on the host page.
- **Re-theme:** change the variables in `:root`.
- **Font:** Montserrat loads from Google Fonts via a `<link>` in each page head (needs internet; falls back to system fonts). Remove it or self-host for fully offline use.
- **Printing:** use the browser's print dialog; navigation is hidden and sections avoid page splits.

Validate with https://validator.w3.org/nu/ before publishing.
