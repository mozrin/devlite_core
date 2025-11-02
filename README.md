## 🧱 Devlite Blank Setup

To get started with **Devlite Blank**, make sure your `.devcontainer/devcontainer.json` file has the correct workspace folder path.

### 🔧 Step 1: Update `workspaceFolder`

Open `.devcontainer/devcontainer.json` and locate this line:

```json
"workspaceFolder": "/READ the README.md file",
```

Replace it with the actual name of your project directory. For example, if your project is named `my_project`, update it to:

```json
"workspaceFolder": "/my_project",
```

### 🔄 Step 2: Reload in Dev Container

After saving the file:

1. Close the folder in VS Code.
2. Reopen the folder.
3. When prompted, click **“Reopen in Container”**.

That’s it — you’re now running inside **Devlite Blank**:
Ubuntu 22.04, MariaDB, Redis, and subtle perfection.
