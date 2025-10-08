# 🐙 GitHub Guide for Complete Beginners

## 🎯 What is GitHub and Why Do You Need It?

**GitHub** is like Google Drive for code and projects. It:
- **Saves your work safely** in the cloud (no lost files!)
- **Publishes your dashboard online** so anyone can view it
- **Tracks your progress** with a complete history of changes
- **Looks professional** to employers who see your GitHub profile

**Think of it as:** Your professional portfolio storage that also backs up your work.

---

## 🚀 Setting Up Your Project (Do This Today!)

### Step 1: Create Your GitHub Account
**If you don't already have one:**
1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. Use your **school email** to get education benefits
4. Choose a **professional username** (employers will see this!)

### Step 2: Create Your EBM Dashboard Repository
1. **Sign in to GitHub**
2. **Click the green "New" button** (top left)
3. **Repository name:** `ebm-dashboard-[your-eID]` (example: `ebm-dashboard-smith21`)
4. **Description:** "Evidence-Based Management Dashboard - MGT357 Fall 2025"
5. **Make it Public** (required for GitHub Pages)
6. **Check "Add a README file"**
7. **Click "Create repository"**

### Step 3: Enable GitHub Pages (Make Your Dashboard Live Online!)
1. **In your repository,** click "Settings" tab (top menu bar)
2. **Scroll down to "Pages"** (in left sidebar under "Code and automation")
3. **Under "Source," select "Deploy from a branch"**
4. **Branch dropdown: select "main"** (should be the only option)
5. **Folder: leave as "/ (root)"**
6. **Click "Save"**
7. **SUCCESS!** You'll see "Your site is ready to be published at [URL]"
8. **Wait 2-3 minutes** for deployment to complete
9. **Visit your live dashboard** at: `https://[your-username].github.io/[repository-name]`
10. **Bookmark this URL** - you'll use it all semester!

**🔧 Troubleshooting Pages Setup:**
- If "Pages" section is missing, make sure repository is Public
- If deployment fails, check that `index.html` file exists in your repository
- If dashboard looks broken, wait 5 minutes and refresh (CSS needs time to load)

---

## 📁 Adding Your Dashboard Files

### Method 1: Upload Through Web Browser (Easiest for Beginners)
1. **In your empty repository,** look for "Quick setup" section with "uploading an existing file" link
2. **Click "uploading an existing file"**
3. **Select ALL your project files:**
   - Click "choose your files"
   - Navigate to your project folder
   - Select ALL files (Ctrl+A or Cmd+A) including:
     - `index.html` (your dashboard file)
     - `content/` folder with all your .txt files
     - `README.md`, `PROJECT_TRACKER.md`, etc.
     - All other template files from your download
   - Click "Open"
4. **Verify all files are listed** for upload (you should see 25+ files including the content folder files)
5. **Scroll down** and add commit message: "Initial dashboard setup"
6. **Click "Commit changes"**
7. **Wait for upload to complete** - all your files should now be visible in your repository!

**Alternative if above doesn't work:**
- Click "Add file" → "Upload files"
- Drag individual files or select multiple files
- Include all the same files listed above
- Same commit message and process

### Method 2: Using VS Code (For Advanced Users)
**This method is more complex - use Method 1 unless you're comfortable with Git:**

1. **Install Git** on your computer (if not already installed)
2. **In VS Code,** open Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
3. **Type "Git: Clone"** and select it
4. **Paste your repository URL** (from GitHub)
5. **Choose a local folder** to store your project
6. **Copy your template files** into this cloned folder
7. **In VS Code Source Control panel:**
   - Stage all changes (+ icon next to files)
   - Add commit message: "Initial dashboard setup"
   - Click "Commit" 
   - Click "Sync Changes" to upload to GitHub

**Note:** This method requires Git knowledge. Beginners should use Method 1.

---

## 🔄 Daily GitHub Workflow

### Every Time You Work on Your Project:
1. **Make your changes** in VS Code
2. **Save your files** (`Ctrl+S` or `Cmd+S`)
3. **Open Source Control** in VS Code
4. **Stage your changes** (click + next to changed files)
5. **Write a commit message** describing what you did
6. **Click "Commit"**
7. **Click "Sync Changes"** to upload to GitHub

### Good Commit Messages:
✅ "Added scientific evidence sources and appraisal"  
✅ "Completed ASK phase problem definition"  
✅ "Updated stakeholder analysis with interview data"  
✅ "Fixed dashboard styling issues"  

❌ "updates"  
❌ "stuff"  
❌ "changes"  

---

## 📱 Accessing Your Live Dashboard

### Your Dashboard URLs:
**GitHub Repository:** `https://github.com/[your-username]/[repository-name]`  
**Live Dashboard:** `https://[your-username].github.io/[repository-name]`

**Example:**
- Repository: `https://github.com/smith21/ebm-dashboard-smith21`
- Live Dashboard: `https://smith21.github.io/ebm-dashboard-smith21`

### Sharing Your Work:
- **For classmates/instructor:** Share your live dashboard URL
- **For technical help:** Share your repository URL
- **For portfolio:** Use either URL (repository shows your process, dashboard shows the result)

---

## 🛠️ VS Code + GitHub Integration

### First-Time Setup:
1. **Open VS Code**
2. **Sign in to GitHub:**
   - Click the profile icon (bottom left)
   - Choose "Sign in to GitHub"
   - Follow the prompts
3. **Clone your repository:**
   - Press `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac)
   - Type "Git: Clone"
   - Paste your repository URL
   - Choose a folder on your computer

### Working with Your Project:
1. **Open your project folder** in VS Code
2. **Edit your files** normally
3. **Use Source Control panel** to manage GitHub sync
4. **Your changes appear online** within minutes

---

## 🎯 File Organization Best Practices

### Recommended Structure:
```
your-repository/
├── index.html (or dashboard.html)
├── README.md
├── PROJECT_TRACKER.md
├── content/
│   ├── ask-problem-definition.txt
│   ├── ask-stakeholder-analysis.txt
│   ├── ask-success-criteria.txt
│   ├── evidence-scientific-methods.txt
│   ├── evidence-scientific-sources.txt
│   ├── evidence-scientific-appraisal.txt
│   ├── [all other content files...]
└── assets/ (optional)
    ├── images/
    └── custom-styles.css
```

### File Naming Rules:
- **Use lowercase letters**
- **Use hyphens instead of spaces**
- **No special characters** (only letters, numbers, hyphens)
- **Include file extensions** (.html, .txt, .md, .css)

---

## 🆘 Common GitHub Problems & Solutions

### 🚫 Problem: File upload not working or files missing
**Solution:**
1. **If "uploading an existing file" link is missing:** Click "Add file" → "Upload files" instead
2. **If folder upload fails:** Select individual files rather than the whole folder
3. **If some files didn't upload:** Check the file list before committing - re-upload missing files
4. **If content folder is missing:** Make sure to select files INSIDE the content folder, not just the folder itself

### 🚫 Problem: "Repository not found" or permission errors
**Solution:**
1. Check you're signed in to the correct GitHub account
2. Verify the repository URL is correct
3. Make sure the repository is public, not private

### 🚫 Problem: Changes not showing on live dashboard
**Solution:**
1. Wait 5-10 minutes for GitHub Pages to update
2. Hard refresh your browser (`Ctrl+F5` or `Cmd+Shift+R`)
3. Check that your main file is named `index.html`

### 🚫 Problem: Can't push changes from VS Code
**Solution:**
1. Make sure you're signed in to GitHub in VS Code
2. Check your internet connection
3. Try the "Sync Changes" button instead of "Push"
4. If using HTTPS, you may need a Personal Access Token

### 🚫 Problem: Accidentally deleted important files
**Solution:**
1. **Don't panic!** GitHub keeps a complete history
2. Go to your repository on GitHub
3. Click the file name that was deleted
4. Click "History" to see previous versions
5. Click on a previous commit to restore the file

---

## 🔐 GitHub Education Benefits

### What You Get:
- **GitHub Pro** features for free
- **Unlimited private repositories**
- **GitHub Copilot Pro** access
- **GitHub Pages** for unlimited public repositories

### How to Activate:
1. Go to [education.github.com](https://education.github.com)
2. Click "Get benefits"
3. Verify with your .edu email address
4. Upload documentation if requested
5. Wait for approval (usually 1-3 days)

---

## 👥 Collaboration & Sharing

### For This Class:
- **Keep your repository public** so instructor can access it
- **Share your live dashboard URL** for content review
- **Share your repository URL** for technical help

### Professional Use:
- **Your GitHub profile** becomes part of your professional portfolio
- **Employers can see** your project organization and development process
- **Use descriptive commit messages** to show your thinking process
- **Include good README files** to explain your projects

---

## 📊 Tracking Your Progress

### GitHub Shows Your Activity:
- **Green squares** on your profile show daily activity
- **Commit history** shows your development process
- **File history** tracks changes to individual files
- **Issues and milestones** can track project progress

### Professional Benefits:
- **Demonstrates consistency** with regular commits
- **Shows problem-solving skills** through commit messages
- **Displays technical competence** with proper file organization
- **Provides portfolio evidence** of project management abilities

---

## 🎯 Success Tips

### Daily Habits:
- **Commit changes daily** (even small ones)
- **Write clear commit messages** 
- **Sync regularly** to avoid conflicts
- **Check your live dashboard** to make sure everything works

### Professional Development:
- **Use a professional repository name**
- **Write clear documentation** in your README
- **Organize files logically**
- **Update your progress tracker** regularly

### Getting Help:
- **Repository URL** for technical issues
- **Live dashboard URL** for content feedback
- **Specific error messages** for troubleshooting
- **Screenshots** when something looks wrong

---

## 🚀 Quick Start Checklist

**Today (Get Set Up):**
- [ ] Create GitHub account (if needed)
- [ ] Create your EBM dashboard repository  
- [ ] Enable GitHub Pages
- [ ] Upload template files
- [ ] Verify your live dashboard works
- [ ] Share repository URL with instructor

**This Week (Start Building):**
- [ ] Set up VS Code + GitHub integration
- [ ] Begin editing content files
- [ ] Make your first commits with meaningful messages
- [ ] Update your PROJECT_TRACKER.md
- [ ] Test that changes appear on your live dashboard

**Ongoing (Professional Habits):**
- [ ] Commit changes daily
- [ ] Write clear commit messages
- [ ] Keep files organized
- [ ] Update documentation regularly
- [ ] Share progress with classmates and instructor

---

**Remember:** GitHub might seem intimidating at first, but it's just fancy file storage with version control. Start simple, practice regularly, and you'll quickly develop professional-level skills! 🎯
