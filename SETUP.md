# GitHub Setup Instructions

Your Claude tasks repository is ready to push to GitHub! Follow these steps:

## Step 1: Create the Repository on GitHub

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `claude-tasks` (or whatever you prefer)
3. Description: "Central repository for Claude-related projects, automations, and skills"
4. Choose: **Private** (if you want to keep it private) or **Public**
5. Do NOT initialize with README, .gitignore, or license (we already have these)
6. Click **Create repository**

## Step 2: Push to GitHub

After creating the repo, GitHub will show you commands. Follow this:

```bash
# Navigate to the repo directory
cd ~/Documents/Claude  # or wherever you cloned it

# Initialize git and set up remote
git init
git add .
git commit -m "Initial commit: Claude tasks, AV monitoring, and automation setup"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/claude-tasks.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## Step 3: Update README.md

After pushing, go to your repo and edit the README.md to add your GitHub URL:
```markdown
- **GitHub:** https://github.com/YOUR-USERNAME/claude-tasks
```

## Step 4: Start Using It

Clone to any machine:
```bash
git clone https://github.com/YOUR-USERNAME/claude-tasks.git
cd claude-tasks
```

## Ongoing Workflow

1. Update brand lists, add reports, document new automations
2. Commit changes regularly:
   ```bash
   git add .
   git commit -m "Update: [what changed]"
   git push
   ```

3. Archive daily reports in `/av-monitoring/daily-reports/` as they accumulate

## Tips

- Use meaningful commit messages for tracking changes over time
- Archive old daily reports to keep the main folder clean
- Update `scheduled-tasks.md` whenever you create or modify automations
- Link trigger IDs for easy reference and modification
