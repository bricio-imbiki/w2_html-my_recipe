# LAB: My Recipe

**HTML - Week 2**

In this lab you will create a page for a recipe you love.  
By the end of the lab you should have an index.html that looks like this in the browser:  
<img src="assets/result.png" width="50%" height="" style="margin-x: auto">

⚠️ Please read the plan before starting the lab.

1. Fork the repository, and clone
2. Install Live Server extension in VS code
3. Do every exercice in their own branches
4. Merge all of your work in a newly created branch and publish

## 1. Fork the Repository, and clone

To get started with the lab, you need to fork the repository:

1. Click on the **Fork** button at the top-right corner of the repository page.
2. Select your **GitHub account** to create a copy in your own repositories.
3. Once forked, clone the repository to your local machine using:
   ```bash
   git clone <your-forked-repo-url>
   ```
4. Navigate into the project folder:
   ```bash
   cd my-recipe-lab
   ```

## 2. New Tool: Live Server + VS Code

For this lab, we will use the **Live Server** extension in VS Code to preview our HTML changes in real time.

### What is Live Server?

Live Server is a **VS Code extension** that allows you to launch a local development server with **auto-refresh** whenever you save changes to your HTML file.

### How to Install & Use Live Server

1. Open **VS Code**.
2. Go to **Extensions** (Ctrl+Shift+X or Cmd+Shift+X on Mac).
3. Search for **Live Server** and install it.
4. Open your **HTML file** in VS Code.
5. Right-click and select **"Open with Live Server"**, OR click on the **"Go Live"** button in the status bar.
6. Your browser will open with the live preview of your file.

---

## 3. Exercices

Now we can start the lab.  
The page you will create is divided into 5 parts:  
<img src="assets/sections.png" width="50%" height="" style="margin-x: auto">

**For every exercise/section you will** 
**- checkout the associated branch**  
**- read the intrcutions to build the section in the readme.md** . 
**- edit the index.html file and commit** . 

**Below are the names of the branches for every section:** . 
**ex1: `header-setup`**  
**ex2: `ingredients`**  
**ex3: `steps`**  
**ex4: `links`**  
**ex5: `paragraph`**  

**Now, until you finish the exerice/section 5, you can leave this readme.md instruction.**  
⚠️⚠️**Once you've finished the section 5, remember to return to this readme.md (main branch) to continue the lab**


## 4. Merge and publish

Once you finished all exercises, merge them into a new branch named `total-merge`:

1. create the `total-merge` branch from the `main` branch:
   ```bash
   git checkout main
   git checkout -b total-merge
   git checkout total-merge
   ```

   # TO DO
2. merge header-setup
   ```bash
   git merge header-setup
   ```

3. Merge your branch:
   ```bash
   git merge <branch-name>
   ```
4. Push your changes to GitHub:
   ```bash
   git push origin main
   ```

Good luck and have fun building your recipe page! 🍽️

