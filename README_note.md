## 🧭 GitHub Pages Case Sensitivity Notice

This repository is named **Promptable-Machine**, so GitHub Pages serves it at:

➡️ **https://kj-sv.github.io/Promptable-Machine/**

GitHub Pages URLs are **case-sensitive** after `github.io`, which means:

- ✅ Works → `https://kj-sv.github.io/Promptable-Machine/`
- ❌ 404 Error → `https://kj-sv.github.io/promptable-machine/`

### 🛠 Why
GitHub treats repository names as part of the folder path. If the capitalization differs, the request is routed to a non-existent project, and the global 404 page appears before any local `404.html` can load.

### ✅ Optional Fix
If you ever want the lowercase version to work:

1. Go to **Settings → General → Repository name**.  
2. Rename the repo to **`promptable-machine`** (all lowercase).  
3. Double-check **Settings → Pages** still deploys from `main / (root)`.  
4. Wait about a minute for the redeploy.

After renaming, the canonical URL will become:  
**https://kj-sv.github.io/promptable-machine/**

### ℹ️ Tip
You can keep both the current capitalized name and this note so collaborators and visitors understand why lowercase links 404.
