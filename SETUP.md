# Put this on your GitHub profile

This folder is the profile README project for [`astra-chanUwU`](https://github.com/astra-chanUwU).

GitHub only displays a profile README when all three names match exactly:

- your account: `astra-chanUwU`
- the repository: `astra-chanUwU`
- the default branch: usually `main`

## 1. Review it locally

```sh
cd /Users/astrochan/Documents/Workstation/astra-chanUwU
open README.md
```

Edit the copy, project links, and any personal details before publishing. The generated banner lives at `assets/astral-banner.svg`.

## 2. Create the repository on GitHub

Create a **public** repository named exactly `astra-chanUwU` under your account. Leave “Add a README”, `.gitignore`, and license unchecked because this folder already contains the files.

## 3. Commit and push

From this folder:

```sh
git init -b main
git add README.md SETUP.md assets/ .gitignore
git commit -m "Create Astra-chan profile README"
git remote add origin git@github.com:astra-chanUwU/astra-chanUwU.git
git push -u origin main
```

If you prefer HTTPS, use this remote instead:

```sh
git remote add origin https://github.com/astra-chanUwU/astra-chanUwU.git
```

Or let the GitHub CLI create the public repository and push the commit in one step:

```sh
gh repo create astra-chanUwU/astra-chanUwU --public --source=. --remote=origin --push
```

Use either the website flow or the `gh repo create` flow, not both.

After the push, open `https://github.com/astra-chanUwU` and GitHub should render this README on your profile. The stats cards are powered by public read-only image endpoints; if one is temporarily unavailable, the rest of the profile still works.
