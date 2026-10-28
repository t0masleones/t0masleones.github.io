# Tomás Antonio · Portfolio

Personal site and CV of Tomás Antonio, Business Analyst & Product Owner for financial services.

**Live:** https://t0masleones.github.io

- `index.html` — the portfolio, in English and Portuguese (toggle in the header, or `?lang=pt`)
- `cv/Tomas-Antonio-CV-EN.pdf` · `cv/Tomas-Antonio-Curriculo-PT.pdf` — downloadable CVs
- `cv/src/` — HTML sources of the CVs

## Regenerate the CV PDFs (Windows, Microsoft Edge)

```powershell
$edge = "C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe"
& $edge --headless=new --no-pdf-header-footer --print-to-pdf="cv\Tomas-Antonio-CV-EN.pdf" "file:///$PWD/cv/src/cv-en.html"
& $edge --headless=new --no-pdf-header-footer --print-to-pdf="cv\Tomas-Antonio-Curriculo-PT.pdf" "file:///$PWD/cv/src/cv-pt.html"
```
