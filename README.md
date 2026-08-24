# Ba-Hoa Thai academic homepage

Source for the GitHub Pages site published at **https://thaihoabkdn.github.io/**.

## Files

- `index.html` - the whole page
- `styles.css` - styling

## Publishing

The site is served by GitHub Pages from the `main` branch of
`ThaiHoaBKDN/ThaiHoaBKDN.github.io` (repository root).

To update the live site:

```bash
git add -A
git commit -m "Update site"
git push
```

GitHub rebuilds and republishes within a minute or two.

If you change `styles.css`, bump the version number in the `index.html`
stylesheet link (`styles.css?v=3` -> `?v=4`). Browsers cache the stylesheet
for 10 minutes, and this forces them to fetch the new one right away.

## Update later

- Swap `hoa.jpg` for a different portrait if desired (keep the same filename, or update `index.html`).
- Add an email address only if you want it public.
- Update the publication list from ORCID when new works are added.

Sources used:

- Reference layout: https://thachdo.github.io/
- ORCID profile: https://orcid.org/0009-0009-1415-0070
