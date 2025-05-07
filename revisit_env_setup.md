
# 🧪 ReVISit Python Bindings — Environment Setup Guide

Welcome! **ReVISit Python Bindings** is an internal tool designed for operators of ReVISit to leverage Jupyter’s analytical capabilities for deeper insights into study results — especially useful for AI/ML and data science workflows.

## ⚙️ Setup Instructions

### 1. Install Visual Studio Code (VSCode) and Required Extensions

- **Download VSCode**:  
  [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
  
- **Within VSCode**, install the following extensions:
  - **Python** (by Microsoft)
  - **Jupyter** (by Microsoft)

> You can find these in the **Extensions Marketplace** (left sidebar, or `Ctrl+Shift+X`).

---

### 2. Clone the Repository

1. Navigate to the repository on GitHub.
2. **Create a branch** off of the main branch.
3. Click **"Code" → "Clone"** to get the repository URL.
4. Open VSCode → `Ctrl+Shift+P` → **Git: Clone**, then paste the repo URL.

---

### 3. Install Required Packages

Open the integrated terminal in VSCode (`Ctrl+\``) and run:

\`\`\`bash
pip install revisitpy
pip install revisit
pip install revisit_server
\`\`\`

---

### 4. Sync the Environment

Still in the terminal, run:

\`\`\`bash
uv sync
\`\`\`

> 💡 This will ensure your virtual environment is aligned with the tool’s dependencies.

---

### 5. Run and Debug Studies

If setup was successful, you should now be able to execute and debug studies directly in VSCode’s Jupyter environment.

---

### 🛠 Troubleshooting

If you encounter errors during execution:

- Check the **terminal** for any missing dependencies.
- Manually install missing packages using:

\`\`\`bash
pip install <missing_package_name>
\`\`\`
