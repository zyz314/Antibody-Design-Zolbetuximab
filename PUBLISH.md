# Publish to GitHub Pages

This folder is already a local Git repository on branch `main`.

## 1. Create the GitHub repository

Create a new public repository under your GitHub account:

```text
zyz314/Antibody-Design-Zolbetuximab
```

Do not initialize it with a README, license, or `.gitignore`; this local folder already contains the project files.

## 2. Push the local site

Run these commands from this folder:

```powershell
git remote add origin https://github.com/zyz314/Antibody-Design-Zolbetuximab.git
git push -u origin main
```

If the remote already exists, use:

```powershell
git remote set-url origin https://github.com/zyz314/Antibody-Design-Zolbetuximab.git
git push -u origin main
```

## 3. Enable GitHub Pages

In the GitHub repository:

```text
Settings -> Pages -> Build and deployment
Source: Deploy from a branch
Branch: main
Folder: / root
Save
```

The site URL should become:

```text
https://zyz314.github.io/Antibody-Design-Zolbetuximab/
```

## 4. Public-release check

Before making the repository public, confirm that the antibody sequences, PDB files, antigen/reference labels, and analysis figures are intended for public disclosure.
