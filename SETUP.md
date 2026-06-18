# GitHub Profile Setup Guide

## Quick Start

### 1. Create the Profile Repository

Your profile repository **must** have the same name as your GitHub username:

```
bharatjidubey
```

Make it **Public** and initialize it with a README.

---

### 2. Repository Structure

```
bharatjidubey/
├── README.md              ← What visitors see on your profile
├── profile-data.json      ← All your personal data (edit this!)
├── editor.html            ← Visual editor (double-click to open)
├── banner.svg             ← Header banner graphic
├── footer.svg             ← Footer banner graphic
├── .gitignore
├── LICENSE
├── SETUP.md
├── CUSTOMIZATION.md
└── .github/
    └── workflows/
        ├── snake.yml      ← Contribution snake animation
        └── metrics.yml    ← GitHub metrics dashboard
```

---

### 3. How to Make Changes

**Option A — Visual Editor (Recommended)**

1. Double-click `editor.html` to open it in your browser.
2. Edit your details using the form fields.
3. Click **"📂 Load profile-data.json"** to import your current data.
4. Make your changes.
5. Click **"💾 Save profile-data.json"** to download the updated data.
6. Click **"📄 Download README.md"** to download the generated README.
7. Click **"🎨 Download banner.svg"** to download the generated header banner.
8. Click **"🎨 Download footer.svg"** to download the matching footer banner.
9. Replace the files in your repository and push to GitHub.

**Option B — Direct JSON Edit**

1. Open `profile-data.json` in VS Code.
2. Edit the values you want to change.
3. Open `editor.html` in your browser.
4. Load the JSON → Download the new README.
5. Push both files to GitHub.

---

### 4. Enable GitHub Actions

The snake animation and metrics require GitHub Actions:

1. Go to your repository on GitHub.
2. Click **Settings** → **Actions** → **General**.
3. Under "Workflow permissions", select **Read and write permissions**.
4. Click **Save**.
5. Go to the **Actions** tab and manually run both workflows once.

---

### 5. Pin Your Best Repositories

Go to your GitHub profile and click **"Customize your pins"**. Recommended order:

1. DEADRYX
2. AI Finance Manager
3. Portfolio (when ready)
4. DSA Python (when ready)

---

### 6. Keep It Updated

- Push code regularly to keep the contribution graph green.
- Update `profile-data.json` whenever you complete a project or earn a certification.
- Re-run the editor to regenerate `README.md`.

Happy coding! 🚀
