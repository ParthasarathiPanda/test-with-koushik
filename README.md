# test-with-koushik

Simple Flask example that displays a "Merry Christmas" page with a festive image.

This repository contains two ways to view the Merry Christmas page:

- Dynamic (Flask): run the small Flask app locally using `app.py`.
- Static (GitHub Pages): a ready-to-serve static site is available at the repository root.

GitHub Pages hosting (recommended for a simple static greeting):

1. Make sure the `index.html` and the `static/` folder are on the `main` branch (they are already in this repo).
2. In the repository Settings -> Pages, choose `main` branch and `/ (root)` as the publishing source.
3. Save. GitHub will build and publish the site; your page will be live at `https://<your-username>.github.io/<repo-name>/`.

Run Flask locally (optional):

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Open http://localhost:5000 to view the Flask-served page.
