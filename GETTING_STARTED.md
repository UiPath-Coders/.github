# Getting Started: Creating and Working on a UiPath-Coders Project

This guide walks you through creating a new repository from the org template, setting it up in UiPath Studio, and making your first commit.

---

## Step 1 — Name your repository

Before creating anything, decide on a name following the org convention (see [NAMING_CONVENTION.md](./NAMING_CONVENTION.md)):

```
[vertical]-[use-case]-[type]
```

Examples: `hls-claims-automation`, `pharma-complaint-classifier`, `shared-doc-understanding`

Rules: lowercase + hyphens only, valid vertical prefix, under 40 characters.

---

## Step 2 — Create the repository from the template

1. Go to **https://github.com/UiPath-Coders/template-uipath-project**
2. Click **"Use this template"** → **"Create a new repository"**
3. Set the owner to **UiPath-Coders**
4. Enter your repository name from Step 1
5. Set visibility to **Private** (default for project repos)
6. Click **"Create repository"**

> Do NOT click "Initialize this repository with a README" — the template already provides one.

---

## Step 3 — Clone your repo

```bash
git clone https://github.com/UiPath-Coders/<your-repo-name>.git
```

1. Navigate to the cloned folder and start building your project

---

## Step 4 — Fill in the README

Open `README.md` and replace the placeholder sections:

- `[Project Name]` → your repo name in readable form
- One-sentence description
- Prerequisites (Studio version, Orchestrator URL, NuGet packages)
- Owner details (vertical, primary contact)

---

## Step 5 — Make your first commit



1. Push to `main`



---

## Step 6 — Set up your working branch (optional)

Once `main` has the initial commit:

```bash
git checkout -b develop
git push -u origin develop
```

For day-to-day work, branch off `develop`:

```bash
git checkout -b feature/your-name-short-description develop
```

Never commit directly to `main`.

---


## Checklist before your first push

- [ ] Repo named following the convention
- [ ] README placeholders filled in
- [ ] `.gitignore` in place (comes from template — do not modify without team review)
- [ ] No `.env`, `credentials.json`, Orchestrator tokens, or `appsettings.Production.json` staged

