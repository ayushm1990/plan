# Diet Plan Generator

A lightweight, single-page web app that calculates BMI from age, height, and weight, and suggests a simple sample diet plan based on the result.

No build tools, no dependencies, no backend — just one HTML file.

## Live demo

Once this repo is pushed to GitHub and Pages is enabled (see below), it will be live at:

```
https://<your-username>.github.io/<repo-name>/
```

## Features

- BMI calculation from height and weight
- Three-tier diet suggestions: Underweight / Normal Weight / Overweight
- Input validation (rejects empty, zero, or negative values)
- Mobile-friendly viewport scaling

## Running locally

Just open `index.html` in any browser:

```bash
open index.html        # macOS
start index.html       # Windows
```

> **iPhone/iPad note:** Don't open the file directly from the Files app — that uses Quick Look, which blocks JavaScript and will make the button appear to do nothing. Either:
> - Open it through **Safari** (Files app → tap and hold the file → Share → Open in Safari), or
> - Use the GitHub Pages link above once deployed, which always opens in a real browser.

## Deploying with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. On GitHub, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Pushing this project to GitHub

From inside this folder:

```bash
git init
git add .
git commit -m "Initial commit: diet plan generator"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Replace `<your-username>` and `<repo-name>` with your actual GitHub username and the repository name you create.

## Disclaimer

This tool provides a general BMI estimate and generic sample meal ideas. It is not medical or nutritional advice. Consult a registered dietitian or doctor before making significant dietary changes.

## License

MIT
