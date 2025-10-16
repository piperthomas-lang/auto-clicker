Project: Responsive Layout Example

Quick local run:
- Save index.html and styles.css in the same folder.
- Open index.html in a browser, or run a simple local server (recommended):

  # Using Python 3:
  python3 -m http.server 8000
  # then open http://localhost:8000

  # Using npm live-server (install first):
  npm install -g live-server
  live-server

- Make changes, refresh to see updates. Use Live Server in VS Code for auto-reload.

Git & GitHub:
- git init
- git add .
- git commit -m "Initial site"
- Create a GitHub repo, add as remote, then:
- git branch -M main
- git remote add origin <YOUR_REPO_URL>
- git push -u origin main

Deploy options:
- GitHub Pages: enable Pages in repo Settings (branch: gh-pages or main/docs).
- Netlify: drag & drop folder in Netlify dashboard or connect GitHub repo; publish dir = /.
- Vercel: import repo on Vercel, framework = static, build step = none.

Optional: set up a GitHub Action to auto-deploy to GitHub Pages (see .github/workflows/ in examples).
