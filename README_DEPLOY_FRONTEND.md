# Deploying Your Frontend (index.html) on Vercel

1. **Create a new Vercel project** (do not use the backend Python project).
2. Place your `index.html`, CSS, JS, and all assets in the root folder (or a `public` folder).
3. Add the provided `vercel.json` file to the project root.
4. Deploy using the Vercel CLI or the Vercel dashboard.

## Important

- **Update all API URLs in your JS to use your deployed backend URL.**
  Example:
  ```js
  const API_BASE = "https://your-backend.vercel.app";
  fetch(`${API_BASE}/api/process`, { ... });
  ```
- Do **not** use `localhost` in your deployed frontend.

## Folder structure example

```
/index.html
/style.css
/script.js
/vercel.json
/README_DEPLOY_FRONTEND.md
```

## Deploy

- Run `vercel` in this folder, or drag-and-drop the folder in the Vercel dashboard.

