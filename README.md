# AI Startup Website 🚀

## First DevOps Project

Welcome to this hands-on guide! 🎉  
This tutorial walks you through creating a GitHub repository, cloning it locally, making changes on **main**, working with different branches, and pushing your work to GitHub.  

You’ll also see collaboration between two engineers: **Tom** and **Jerry**. Each step includes screenshots so you can follow along visually. 🙌


---

## Step 1: Create a new GitHub repository 🏗️
On GitHub, click **New** and fill out your repo details (name, description, visibility).  
Then click **Create repository**.

![Step 1](New%20Repo%20created.png)


---

## Step 2: Copy the repository clone URL 🔗
On the repo page, open the **Code** dropdown and copy the **HTTPS** URL.  
We’ll use this to clone the project locally.

![Step 2](Git%20repo%20cloned%20from%20Github.png)


---

## Step 3: Prepare a local project folder 📁
Create a workspace folder, then a project folder, and move into it:

```bash
cd documents
mkdir Darey-Training
cd Darey-Training
mkdir git-project
cd git-project
```

![Step 3](git-project%20directory%20created.png)


---

## Step 4: Clone the repository 📥
Use the URL you copied to clone the repo:

```bash
git clone https://github.com/your-username/ai-startup-website.git
```

![Step 4](Git%20repo%20cloned%20from%20Github.png)


---

## Step 5: Create your first file and add content ✍️
Move into the repo and create an `index.html` file with initial content:

```bash
cd ai-startup-website
touch index.html
echo "This is the Admin creating an index.html file for Tom and Jerry" >> index.html
cat index.html
```

![Step 5](index.html%20file%20created%20and%20content%20added..png)


---

## Step 6: Check status and stage the file ✅
See what changed, then stage the file for commit:

```bash
git status
git add index.html
git status
```

![Step 6](index.html%20file%20staged.png)


---

## Step 7: Commit and push to `main` ⬆️
Make your first commit and push to GitHub:

```bash
git commit -m "This is my first commit"
git push origin main
```

![Step 7](index.html%20file%20commited%20and%20pushed%20to%20Github.png)


---

## Step 8: Verify on GitHub 👀
Refresh the repo page—you should see `index.html` and your commit history.

![Step 8](Update%20after%20index.html%20repo%20was%20pushed%20to%20Github.png)


---

# Tom's Workflow 👨‍💻

## Step 9: Create a new feature branch 🌿
```bash
git checkout -b update-navigation
git branch    # confirm branch
```

![Tom Step 9](update-navigation%20branch%20created.png)


---

## Step 10: Make a change ✨
```bash
echo "This is Tom adding Navigation to the AI-website" >> index.html
cat index.html
git status
git add index.html
git status
```

![Tom Step 10](Content%20added%20to%20the%20index.html%20file%20by%20Tom%20and%20staged.png)


---

## Step 11: Commit and push Tom's branch 📤
```bash
git commit -m "Update navigation bar"
git push origin update-navigation
```

![Tom Step 11](index.html%20file%20commited%20and%20pushed%20to%20Github%20by%20Tom.png)


---

## Step 12: Open a Pull Request 🧭
On GitHub, click **Compare & pull request** for `update-navigation`.  
You can merge from GitHub or via CLI.

![Tom Step 12](Git%20repo%20pulled%20and%20merged%20with%20main%20branch.png)


---

# Jerry's Workflow 👨‍💻

## Step 13: Create another branch 📇
```bash
git checkout -b add-contact-info
git branch    # confirm branch
```

![Jerry Step 13](Jerry's%20add-contact-info%20branch%20created.png)


---

## Step 14: Edit, stage, and commit 🛠️
```bash
echo "Add contact info" >> index.html
cat index.html
git status
git add index.html
git status
```

![Jerry Step 14](Info%20added%20on%20Jerry's%20file%20and%20staged.png)


---

## Step 15: Push Jerry's branch 🚀
```bash
git commit -m "Add contact information"
git push origin add-contact-info
```

![Jerry Step 15](Jerry's%20index.html%20file%20commited%20and%20pushed%20to%20Github.png)


---

## Step 16: See multiple PRs 📨
Now your repo shows banners for both `update-navigation` and `add-contact-info`.  
Open each PR to compare and merge when ready.

![Step 16](update%20of%20Tom%20&%20Jerry's%20push%20on%20Github.png)


---

## 🎯 Summary

This project demonstrates a **real DevOps Git workflow**:  
- ✅ Creating repositories & cloning locally  
- ✅ Making changes on `main`  
- ✅ Creating and switching between branches  
- ✅ Collaborating via pull requests & merges  

By simulating **Tom** and **Jerry’s collaboration**, you’ve practiced the same version control workflows that DevOps engineers use daily.  
This reinforces why **Git + GitHub** are vital for team collaboration, code integrity, and continuous delivery. 🚀
