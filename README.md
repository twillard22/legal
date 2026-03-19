# Legal Pages

Static HTML pages for app privacy policies and terms of service. Designed for GitHub Pages hosting.

## Apps

| App | URLs |
|-----|------|
| **The 10 Phases App** | [Legal](the10phasesapp/) · [Privacy](the10phasesapp/privacy.html) · [Terms](the10phasesapp/terms.html) |

**Service Provider:** Back Nine Bogeys  
**Contact:** trentonwillard22@icloud.com

## Structure

```
/
└── the10phasesapp/
    ├── index.html      # App landing — links to privacy & terms
    ├── privacy.html
    └── terms.html
```

Each app lives in its own directory. Add new apps as separate folders.

## Adding a new app

1. Create a directory (e.g. `myapp/`)
2. Add `index.html`, `privacy.html`, and `terms.html`
3. Update this README with the new app’s URLs

## GitHub Pages setup

1. Create a repo and push this folder
2. **Settings → Pages** → Source: Deploy from branch → Branch: `main` / `/(root)`
3. After deploy, your URLs will be:
   - `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/the10phasesapp/`
   - `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/the10phasesapp/privacy.html`
   - `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/the10phasesapp/terms.html`

Use these URLs in App Store Connect and Google Play Console for your app’s privacy policy and terms links.
