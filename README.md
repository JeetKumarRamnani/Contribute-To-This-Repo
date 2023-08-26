## How to Contribute to This Repo

This repository is about contributing to open source projects on GitHub. Here's how you can contribute to the "Contribute-To-This-Repo" project:

### Step 1: Fork This Project

Click the "Fork" button at the top right corner of the GitHub repository page to create a copy (fork) of the repository under your own GitHub account.

### Step 2: Clone Your Forked Version To Your Computer

Open your terminal or command prompt and use the following command to clone your forked repository to your local machine:

```bash
git clone <your-fork-url>
```

Replace `<your-fork-url>` with the URL of your forked repository.

### Step 3: Add Your Information

Inside the project directory, locate the `index.html` file. Replace the following code block with your details:

```html
<tr class="hover:bg-gray-200">
    <td class="border px-4 py-2">Sagar</td>
    <td class="border px-4 py-2">Karachi</td>
    <td class="border px-4 py-2">Pakistan</td>
    <td class="border px-4 py-2">sagar@gmail.com</td>
    <td class="border px-4 py-2"><a href="https://www.github.com" class="text-blue-500">GitHub</a></td>
</tr>
```

### Step 4: Stage Changes

Navigate to the project directory in your terminal and use the following command to stage the changes you made:

```bash
git add index.html
```

### Step 5: Commit Changes

Commit the staged changes with a meaningful message that includes your GitHub username:

```bash
git commit -m "Added information about me: <Your GitHub Username>"
```

### Step 6: Push Changes to GitHub

Push the committed changes to your forked repository on GitHub:

```bash
git push origin master
```

### Step 7: Create a Pull Request

1. After pushing the changes, go to your forked repository on GitHub.
2. You'll see a notification suggesting that you create a pull request. Click on it to start the process.
3. Review the changes you made.
4. Add a descriptive title and additional comments if needed.
5. Click "Create Pull Request" to send your changes to the original repository.

**Note:** The original repository owner will review your pull request. If everything looks good, they might merge your changes into the main project.

Please replace placeholders like `<your-fork-url>` and `<Your GitHub Username>` with your actual details and GitHub username.

Remember to always check the project's README or CONTRIBUTING file for specific guidelines.

