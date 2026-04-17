# Getting This Site Online

This folder is now the official Academic Pages template. The website will be online after you push it to a GitHub repository named with your GitHub username.

## Fastest path

1. Create or sign in to a GitHub account.
2. Create a new public repository named `jorgepascoa.github.io`.
3. Confirm `_config.yml` uses `jorgepascoa` for the site URL, repository, and GitHub profile.
4. Commit and push this folder to that new repository.
5. Wait a minute or two, then open `https://jorgepascoa.github.io`.

## Commands

Run these from this folder:

```powershell
git remote remove origin
git remote add origin https://github.com/jorgepascoa/jorgepascoa.github.io.git
git add .
git commit -m "Set up academic website"
git branch -M main
git push -u origin main
```

Then check GitHub under **Settings > Pages**. For a repository named `jorgepascoa.github.io`, GitHub Pages normally publishes from the `main` branch automatically.

## What to edit next

- `_config.yml`: site title, sidebar bio, email, GitHub username, Google Scholar, ORCID, and social links.
- `_pages/about.md`: homepage text.
- `_publications/`: publication entries.
- `_talks/`: invited talks and conference presentations.
- `_teaching/`: course entries.
- `images/profile.png`: your sidebar profile photo.
