# Git Workshop - Department of DevOps

Welcome to the Git Workshop! This repository contains a student directory web page designed to help you practice Git and GitHub workflows.

## 📝 Homework Assignment

Your assignment is to add your own student profile card to the directory using Git. Please follow these instructions carefully:

### Step 1: Create a New Branch
Do not work directly on the `main` branch. Create a new branch for your work. Use a descriptive name like `add-[your-name]`.
```bash
git checkout -b add-john-doe
```

### Step 2: Add Your Information
Open `index.html` and add a new card inside the `<div class="badge-grid">` element. You can copy an existing card and replace the placeholder information with your own. 

Here is the HTML structure you should use:
```html
<div class="badge-card">
    <!-- Replace 'Your+Name' with your actual name so the avatar generates correctly -->
    <img src="https://ui-avatars.com/api/?name=Your+Name&size=150&background=1b365d&color=fff" alt="Your Name" class="avatar">
    <h2>Your Name</h2>
    <div class="badge-meta">
        <span class="year">Class of 2026</span>
    </div>
    <button class="profile-btn">View Profile</button>
</div>
```

### Step 3: Commit Your Changes
Stage and commit your changes to your local repository.
```bash
git add index.html
git commit -m "Add [Your Name] to student directory"
```

### Step 4: Push to GitHub and Merge
Push your new branch to the remote repository on GitHub.
```bash
git push -u origin add-john-doe
```
Once pushed, open a **Pull Request (PR)** on GitHub to merge your branch into the `main` branch. After it is reviewed, merge it to complete the assignment!
