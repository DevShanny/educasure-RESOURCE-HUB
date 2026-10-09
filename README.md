# EducaSure Resource Hub

Static site: no build step. Files:

| File | What it is |
| --- | --- |
| `index.html` | The Resource Hub page |
| `logo.png` | EducaSure logo used in the header |
| `onboarding-quiz.html` | Learner onboarding practice quizzes (8 modules) |
| `onboarding-study-guide.pdf` | Learner onboarding study guide |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `educasure-resource-hub`).
2. Upload all files in this folder to the root of the repo (Add file → Upload files → Commit).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source = **Deploy from a branch**, Branch = **main**, Folder = **/ (root)**, then **Save**.
5. After a minute the site is live at `https://<your-github-username>.github.io/educasure-resource-hub/`.

The quiz is also reachable directly at `.../onboarding-quiz.html`.

## Updating

Edit or replace a file in the repo and commit; GitHub Pages redeploys automatically.
Links to SharePoint are in the `QUICK` and `SECTIONS` lists inside the `<script>` in `index.html`.

## Note

GitHub Pages sites are public on the internet unless your organisation uses GitHub Enterprise with private Pages.
The SharePoint links still require an EducaSure login to open.
