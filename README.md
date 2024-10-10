## 🚀 **Step-by-Step Guide for Beginners: How to Contribute to Open Source**

### 📝 **1. Find a Project**
Begin by selecting an open-source project on GitHub. For example, you can explore the [Cal.com GitHub repository](https://cal.com/).  
Navigate to the **Issues** section, and filter by labels like `good first issue` or `bug` to find tasks suitable for beginners.

### 📂 **2. Fork the Repository**
To work on the project, first **Fork** the repository (create your own copy) by clicking the **Fork** button at the top-right of the repository page.

### 💻 **3. Clone the Repository**
After forking, head to your GitHub profile, locate your forked repository, and click the **Code** button to copy the HTTPS URL.  
Clone the repository to your local machine by running the following command in your terminal:

```bash
git clone <your-copied-HTTPS-URL>
```

### 🌿 **4. Create a New Branch**
Avoid making changes directly to the `main` or `master` branch. Instead, create a new branch where you can work on the issue:

```bash
git checkout -b <branch-name>
```

### 🔧 **5. Fix the Issue**
Work on fixing the issue. Modify the necessary files and test your changes locally to ensure everything works smoothly.

### ✅ **6. Stage, Commit, and Push Changes**
Once you're confident with the changes, it's time to stage, commit, and push them. Follow these steps:

1. Initialize Git (if necessary):

   ```bash
   git init
   ```

2. Stage all your changes:

   ```bash
   git add .
   ```

3. Commit your changes with a meaningful message:

   ```bash
   git commit -m "Fixes issue #<issue-id>"
   ```

4. Push your changes to the branch:

   ```bash
   git push origin <branch-name>
   ```

### 🔄 **7. Create a Pull Request (PR)**
Head back to your forked repository on GitHub. You’ll see a **Compare & Pull Request** button. Click it, describe your changes, and mention the issue number like this: `[fixes #issue-id]`.  
Submit the PR and wait for the maintainers to review and merge your contribution.

### 🔄 **8. Sync Your Forked Repository**
Once your PR is merged, you need to keep your forked repository up-to-date with the original project. To do so:

1. Add the original repository as a remote:

   ```bash
   git remote add upstream <original-repo-HTTPS-URL>
   ```

2. Fetch the latest changes:

   ```bash
   git fetch upstream
   ```

3. Checkout your main branch:

   ```bash
   git checkout main
   ```

4. Merge the updates:

   ```bash
   git merge upstream/main
   ```

5. Push the updates to your fork:

   ```bash
   git push origin main
   ```

---

This guide simplifies the process of contributing to open-source projects, offering a structured approach for beginners. Happy coding! 👨‍💻👩‍💻
