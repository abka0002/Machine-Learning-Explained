# Machine Learning to Go

Interactive web app for understanding SMOTE and SMOTE-NC calculations step by step.

## Live Demo

🔗 [View the app on Netlify](https://machine-learning-to-go.netlify.app)

## Deployment Guide — GitHub + Netlify

### Prerequisites

- A GitHub account (you already have the repo `abka0002/Machine-Learning-to-go`)
- A [Netlify](https://www.netlify.com/) account (free tier is fine)
- Git installed on your computer

---

### Step 1 — Clone your repo locally

Open a terminal and run:

```bash
git clone https://github.com/abka0002/Machine-Learning-to-go.git
cd Machine-Learning-to-go
```

### Step 2 — Add the project files

Copy the three files from the download into the repo folder so the structure looks like this:

```
Machine-Learning-to-go/
├── index.html        ← the web app (renamed from SMOTE_and_SMOTE-NC.html)
├── netlify.toml      ← Netlify configuration
└── README.md         ← this file
```

> **Important:** The HTML file must be named `index.html` so Netlify serves it as the homepage.

### Step 3 — Push to GitHub

```bash
git add .
git commit -m "Add SMOTE web app"
git push origin main
```

> If your default branch is `master` instead of `main`, replace `main` with `master` above.

### Step 4 — Connect Netlify to your GitHub repo

1. Go to [app.netlify.com](https://app.netlify.com/) and log in (or sign up free).
2. Click **"Add new site"** → **"Import an existing project"**.
3. Choose **GitHub** as the Git provider.
4. Authorize Netlify to access your GitHub account if prompted.
5. Search for and select **Machine-Learning-to-go**.

### Step 5 — Configure the build settings

On the deploy settings screen, set:

| Setting | Value |
|---------|-------|
| Branch to deploy | `main` (or `master`) |
| Build command | *(leave empty)* |
| Publish directory | `.` |

Then click **"Deploy site"**.

### Step 6 — Wait for deployment

Netlify will deploy your site in a few seconds. You will see a green **"Published"** badge when it is done.

Your site will be live at a random URL like `https://random-name-12345.netlify.app`.

### Step 7 — (Optional) Set a custom site name

1. Go to **Site configuration** → **Site details** → **Change site name**.
2. Enter a name like `machine-learning-to-go`.
3. Your site will now be available at `https://machine-learning-to-go.netlify.app`.

---

### Updating the app

Any time you push changes to GitHub, Netlify will automatically redeploy:

```bash
# Edit index.html, then:
git add .
git commit -m "Update app"
git push
```

---

## Tech Stack

- Pure HTML / CSS / JavaScript (no build step required)
- Hosted on Netlify (free tier)
