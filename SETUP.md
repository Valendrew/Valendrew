# Maintenance and publishing

This directory is an independent Git repository. Run all commands from this directory, never from the parent career repository.

Create the empty **public** repository `Valendrew/Valendrew` on GitHub (do not initialise it with a README, licence or .gitignore), then run:

```bash
cd "/home/valendrew/Projects/resume-portfolio/github-profile/readme"
git remote add origin git@github.com:Valendrew/Valendrew.git
git add .
git commit -m "Add portfolio" 
git push -u origin main
```

If a remote is already attached, inspect `git remote -v` and skip `remote add` when it is correct. Never replace the parent repository's remote. Later updates use `git add .`, `git commit`, and `git push` from this directory.

GitHub displays the root `README.md` on the profile because this public repository matches the username. No Pages configuration is needed here. Portfolio and CV links become live after the separate website is published.

Edit `README.md` directly and keep its project descriptions aligned with the website. This `SETUP.md` is maintenance documentation, not profile content.

[GitHub profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
