# How to Push Your Project to GitHub - ignation99

## Method 1: Install Git (Recommended)

### Step 1: Install Git
Download and install Git for Windows from: https://git-scm.com/download/win

### Step 2: After Installation
After installing Git, come back and we can push your code to GitHub with the following commands:

```bash
# Navigate to project folder (already done)
cd "C:\Users\aliel\OneDrive\Desktop\worldcourse-free-website-template"

# Initialize git (if not already done - but you have .git folder so this might be done)
git init

# Add all files
git add .

# Commit the changes
git commit -m "Initial commit for ignation99"

# Add the GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/ignation99.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## Method 2: Use GitHub Web Interface (No Git Installation)

### Step 1: Create Repository on GitHub
1. Go to https://github.com/new
2. Repository name: `ignation99`
3. Make it Public or Private (your choice)
4. Click "Create repository"
5. **DO NOT** initialize with README, .gitignore, or license

### Step 2: Upload Files
1. After creating the repository, you'll see an upload page
2. Drag and drop your project files from:
   `C:\Users\aliel\OneDrive\Desktop\worldcourse-free-website-template`
3. Click "Commit changes"

### Alternative: Use GitHub Desktop
1. Download GitHub Desktop from: https://desktop.github.com/
2. Sign in with your GitHub account
3. Add the repository from your local folder
4. Push to GitHub

---

## Method 3: Command-Line Alternative (if you install Git later)

Once Git is installed, run these commands in PowerShell or Command Prompt:

```bash
# Navigate to your project
cd "C:\Users\aliel\OneDrive\Desktop\worldcourse-free-website-template"

# Check current status
git status

# Add all files
git add .

# Create commit
git commit -m "Initial commit for ignation99 project"

# Add GitHub remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/ignation99.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## Important Notes

1. **Create the repository first** on GitHub before pushing
2. Replace `YOUR_USERNAME` with your actual GitHub username
3. The repository will be created as `https://github.com/YOUR_USERNAME/ignation99`
4. You may need to authenticate with GitHub (use GitHub username and Personal Access Token, not password)

---

## Quick Install Git

If you want to install Git now:
1. Go to: https://git-scm.com/download/win
2. Download and run the installer
3. Accept all default options during installation
4. After installation, restart your terminal/command prompt
5. Run the commands above

