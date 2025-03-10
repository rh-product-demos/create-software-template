### **🚀 End-to-End Instructions for Setting Up and Editing Your Forked Repository**
_(Fork, open in VS Code, edit, commit, and push – simple and effective!)_

---

## **📌 Pre-requisites**
Before you begin, ensure the following:

### **✅ 1. GitHub CLI (`gh`) is Installed and Authenticated**
To check if GitHub CLI is installed:
```sh
gh --version
```
If it’s **not installed**, follow [GitHub CLI installation instructions](https://cli.github.com/).

Now, check if you're logged into GitHub CLI:
```sh
gh auth status
```
If it says **"You are not logged in"**, run:
```sh
gh auth login
```
_(Follow the prompts to authenticate with GitHub.)_

---

## **📌 Step 1: Fork and Clone the Repository**
1. **Run the following command to fork and clone the repository:**
   ```sh
   gh repo fork rh-product-demos/create-software-template --clone --remote
   ```
   **What This Does:**
   - ✅ **Creates a fork** under your GitHub account (e.g., `your-github-username/create-software-template`).
   - ✅ **Clones your fork to your local machine**.
   - ✅ **Automatically sets up `origin` as your fork**.

2. **Move into the cloned repository:**
   ```sh
   cd create-software-template
   ```

---

## **📌 Step 2: Open the Repository in VS Code**
Now, open the project in VS Code:
```sh
code .
```
_(This will open the repo in VS Code’s Explorer panel.)_

---

## **📌 Step 3: Navigate to the Template Folder and Edit Files**
1. **In VS Code, navigate to:**
   ```
   quarkus-templates/template-quarkus-simple
   ```
2. **Open and edit the following files:**
   - `template.yaml` _(this is currently blank, define your template here)_
   - `catalog-info.yaml` _(this is currently blank, register your template here)_

💡 **You can refer to the existing repo code for structure and examples.**

---

## **📌 Step 4: Commit and Push Your Changes**
Once you've updated the files:

1. **Stage your changes:**
   ```sh
   git add .
   ```
2. **Commit the changes:**
   ```sh
   git commit -m "Updated template.yaml and catalog-info.yaml"
   ```
3. **Push the changes to your forked repository:**
   ```sh
   git push origin main
   ```

---

## **📌 Step 5: Verify Your Changes on GitHub**
1. Go to your forked repo in your browser:
   ```
   https://github.com/YOUR-GITHUB-USERNAME/create-software-template
   ```
2. Check that your edits to **`template.yaml`** and **`catalog-info.yaml`** are present.

---

## **📌 Done! What’s Next?**
- **Register your template in Backstage.**
- **Test if it works with your Backstage setup.**
- **Iterate and refine as needed.**

