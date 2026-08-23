# Self-hosted typefaces

| File | Family | Licence | Source |
|---|---|---|---|
| `instrument-sans-latin.woff2`, `instrument-sans-latin-ext.woff2` | Instrument Sans (variable: wght 400-700, wdth 75-100%) | SIL Open Font License 1.1 | Google Fonts CSS2 API |
| `geist-mono-latin.woff2`, `geist-mono-latin-ext.woff2` | Geist Mono (variable: wght 100-900) | SIL Open Font License 1.1 | Google Fonts CSS2 API |

Retrieved 2026-08-23 from `fonts.googleapis.com/css2` and the
`fonts.gstatic.com` URLs it returned. Only the `latin` and `latin-ext`
subsets are kept; the site is English and German, and German umlauts sit
inside `latin`.

Hosted here rather than linked from the Google CDN so that no visitor IP
address is sent to a third party in order to read a portfolio. The OFL
permits redistribution as part of a larger work; it forbids selling the
fonts on their own, which is not what is happening here.

These replaced Archivo and Fragment Mono. Note when swapping again:
Instrument Sans condenses but cannot expand, so any `font-variation-settings`
above `wdth 100` silently clamps and should be removed rather than left in.
