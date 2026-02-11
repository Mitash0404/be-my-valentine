# Will you be my Valentine?

A simple, one-page Valentine's ask. Host it on GitHub Pages (private repo = not on your profile) and share the link only with her.

## One-time setup (private repo, not on profile)

1. **Create a new repo on GitHub**  
   Go to [github.com/new](https://github.com/new).  
   - Name: e.g. `valentine` or `feb14` (the URL will be `username.github.io/valentine`).  
   - Choose **Private**.  
   - Do **not** add a README, .gitignore, or license (this folder already has files).  
   - Click **Create repository**.

2. **Push this folder** (in terminal, from this folder):
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `REPO_NAME` with your GitHub username and the repo name you chose.

3. **Turn on GitHub Pages**  
   In the repo: **Settings → Pages** → under "Build and deployment", Source: **Deploy from a branch** → Branch: **main** → folder: **/ (root)** → **Save**.

4. **Your page URL** (after 1–2 min):  
   `https://YOUR_USERNAME.github.io/REPO_NAME/`  
   Only people with this link can see it. The repo stays private and won’t show on your profile.
