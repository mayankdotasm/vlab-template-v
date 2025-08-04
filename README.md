# V-Lab Template (Vanilla JS)

A **lightweight and fast** Virtual Lab (V-Lab) template built using **HTML, CSS, and JavaScript**. This template provides a structured framework for developing interactive virtual labs without dependencies on frontend frameworks.

🌐 **Live Demo:** [v-lab-template-vanilla.netlify.app](https://v-lab-template-vanilla.netlify.app/)

---

## 🚀 Features

- **Pure Vanilla JS** – No external dependencies, ensuring simplicity and speed.
- **Minimal & Fast** – Lightweight design for smooth performance.

---

## 📂 Project Structure

```
vlab-template-v/
├── images/      # Static assets (logos, icons, etc.)
├── index.html   # Main HTML file
├── styles.css   # Global styles
├── script.js    # Core JavaScript logic
├── LICENSE      # MIT license
├── .gitignore   # Git ignore file
├── README.md    # Project documentation
└── CONTRIBUTING.md # Contribution and Issues reporting guidelines 
```

---

## ⚙️ Installation & Setup

### 1️. Clone the Repository & Redirect to your repo
or
### 2️. Download ZIP [not recommended]

[Download the latest release as ZIP](https://github.com/mayankdotasm/vlab-template-v/archive/refs/heads/main.zip)

###  Extract & Open

- Extract the downloaded ZIP file to your preferred location.
- Open `index.html` in any modern web browser.
---
## Updating Your V-Lab After Template Patch
The clean way is to treat the template as an upstream remote and regularly pull from it.


### Option 1: (Recommended)

#### Setup (one-time)
```bash
# In your private module repo add template as upstream remote 
git remote add upstream https://github.com/mayankdotasm/vlab-template-v.git
```
#### Fetch & Merge Template Changes
```bash
git fetch upstream
git checkout main   # or your main branch
git merge upstream/main
```
If there are no conflicting customizations → clean merge.

If conflicts exist (because module files were changed differently), Git will show them, and you can manually resolve them.

#### Alternative: Git Rebase (Cleaner History)
```bash
git fetch upstream
git rebase upstream/main 
```
Keeps your custom commits on top of the latest template.
### Option 2: Zip Way (Not Recommended)
 - Downloading the repo as a ZIP and copying files manually loses all Git history.

- Merging future template updates becomes painful and error-prone.
## Why Not Zip & Copy?
Using Git with an upstream remote keeps:
 - Full commit history
 - Easier merging of future patches
 - Cleaner version control workflow

## Need Help?

Open an [issue](https://github.com/mayankdotasm/vlab-template-v/issues) - we're here to help!