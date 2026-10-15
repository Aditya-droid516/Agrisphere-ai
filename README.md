# AgriSphere AI - Vercel deployment

Static site that runs the Streamlit app in the browser (stlite / Pyodide). No server or Python runtime needed on Vercel.

## Deploy
1. Push this folder to a Git repo (GitHub/GitLab/Bitbucket) and import it in Vercel, OR run `npx vercel --prod` here.
2. Framework preset: **Other**. Build command: none. Output directory: `public` (already set in vercel.json).

## Run locally
- As on Vercel:  `cd public && python -m http.server 8000`  then open http://localhost:8000
- As normal Streamlit:  `pip install -r requirements-local.txt && streamlit run public/app.py`

Edit `public/app.py` to change the app; redeploy to publish.
