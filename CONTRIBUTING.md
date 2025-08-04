# Contributing

This repository provides the **base structure** for creating new modules- V-Labs.  
Your contributions help ensure consistency, reliability, and ease of use across all projects.

---

## How You Can Contribute

We welcome contributions in the following areas:
- **Template Structure**: Fix bugs, improve layout, or optimize code in the template itself.
- **Documentation**: Improve clarity, fix typos, or enhance developer guidance.

**Note:** Do **not** add module‑specific logic or features to this template.  
Each new vlab built from this template must maintains its own functionality.

---

## 🐛 Reporting Template Issues

If you find a bug or something missing in the template:
1. Open a **GitHub Issue** in this repository.
2. Provide:
   - A clear description of the problem
   - Steps to reproduce (if applicable)
   - Suggested solution (optional)
3. Mention affected files or components.

**Resources:**  
![GitHub Issues](https://res.cloudinary.com/drnjjbg2a/image/upload/v1754336445/bdfbacca-8ba4-4698-9c41-5e0afa960e3b.png)  
![Good Issue Description Example](https://res.cloudinary.com/drnjjbg2a/image/upload/v1754334330/eafdf853-f879-42e2-aaeb-62090c954bcf.png)

---

## 🔧 Fixing Template Issues (Code Contributions)

1. **Fork** this repository to your GitHub account.  
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/mayankdotasm/vlab-template-v.git
   ```

3. Create a branch for your fix:
   ```bash
    git checkout -b fix/template-issue
   ```

4. Make changes only to the template structure (no module-specific code).

5. Test by creating a fresh module from your modified template.

6. Commit your changes:
    ```bash
    git commit -m "Fix: <short description of change>"
    ```

7. Push and open a Pull Request against the main branch of this repository.
---
## Updating Your Module with Template Patches
When this template is updated, sync your private module using Git upstream:

Option 1: (Recommended)
```bash

# Add template as upstream remote (one-time setup)
git remote add upstream https://github.com/mayankdotasm/vlab-template-v.git

# Fetch and merge changes
git fetch upstream
git checkout main   # or your default branch
git merge upstream/main

# Resolve conflicts, keep your module-specific logic, test thoroughly
```
Option 2: Zip Download (Not Recommended)
1. Download ZIP from this template repository.
2. Manually copy changes into your module.
3. Re-test your module.

_Zip downloading loses Git history and makes future updates harder._

---

## Contribution Guidelines
- Keep scope focused: Fix or enhance the template only.

- Preserve structure: Do not modify the overall layout unless required.
- Write clear commit messages:
    Example: ```Fix: correct content heading hierarchy```

Test your changes: Ensure a new module created from your changes works correctly.

## Need Help❓ 
Open a GitHub [Issue](https://github.com/mayankdotasm/vlab-template-v/issues?q=is%3Aissue) with your question.

