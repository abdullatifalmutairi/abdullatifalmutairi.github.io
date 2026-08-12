# Abdullatif Almutairi - Personal portfolio

Bilingual (English / Arabic) single-page portfolio + printable CV for **Abdullatif Almutairi**, App Developer (Riyadh).

Language toggle sits in the nav. Choice is stored in `localStorage` under `aa-lang`. Arabic uses RTL layout and Cairo type.

## Live (after GitHub Pages)

If published under the personal Pages repo:

- Site: `https://<username>.github.io/`
- CV: `https://<username>.github.io/cv.html`

## Local preview

```bash
cd abdullatifalmutairi.github.io
python3 -m http.server 8765
# open http://127.0.0.1:8765/
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | Portfolio landing page (EN/AR) |
| `cv.html` | Revamped one-page résumé (print → PDF) |
| `assets/portrait.jpg` | Profile photo from original CV |
| `assets/Abdullatif-Almutairi-CV.pdf` | Exportable PDF (when generated) |

## Content source

Derived from the original CV at  
`~/Documents/Abdullatif Almutairi/Abdulatif's Resume.pdf`  
(no invented employers, degrees, or projects).

## Notes

- Spelling on the site uses **Abdullatif** (standard Arabic transliteration). Original PDF used “Abdulatif”.
- Fake skill bars from the old template were replaced with honest skill chips.
- Profile text was tightened; employment and Harfah project facts were kept truthful.
