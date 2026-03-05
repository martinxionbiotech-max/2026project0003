# 2026project0003 - Dental Implant Cost Calculator

A static, deployment-ready webpage for estimating dental implant costs in the **US, Canada, Australia, and the UK**, with all output normalized to **USD**.

## Features

- Country-specific implant pricing model (US / CA / AU / UK)
- Core treatment parameters: implant units, crown type, complexity
- Broad optional cost coverage (consultation, CBCT, extraction, bone graft, sinus lift, sedation, temporary prosthesis, guide, lab premium, follow-up)
- Output includes a median estimate and a ±15% range
- SEO-ready metadata and structured data (JSON-LD)
- Source list, methodology explanation, and disclaimer section

## Local Run

```bash
python3 -m http.server 8000
```

Then open:

`http://localhost:8000/`

## Deployment

### Option 1: GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your branch (e.g., `main`) and root folder (`/root`).
5. `index.html` is the entry point.

### Option 2: Netlify / Vercel
- This is a pure static project, so no build command is required.
- Set publish/output directory to repository root.

## Project Structure

- `index.html`: Full static page (UI, styling, calculator logic, methodology, sources, disclaimer)

## Disclaimer

This tool is for educational and budgeting purposes only. It does not provide medical advice. Final pricing should always come from an in-person clinical evaluation and written quote.
