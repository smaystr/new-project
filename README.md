
# 📘 Setup Instructions for `new-project`

This document describes how to set up a new GitHub repository and create a `development` branch for isolated feature development — based on Jira Ticket **PROM-42164**.

---

## 🛠️ Step-by-step Setup

### 1. Create local project folder
```bash
mkdir new-project
cd new-project
```

### 2. Initialize Git repository
```bash
git init
```

### 3. Create README.md with initial content
```bash
echo "# new-project" > README.md
```

### 4. Stage and commit README.md
```bash
git add README.md
git commit -m "init"
```

### 5. Create `development` branch and switch to it
```bash
git branch development
git checkout development
```

### 6. Add detailed setup instructions to README.md
_(this section you're reading now)_

### 7. Stage and commit with Smart Commit
```bash
git add README.md
git commit -m "PROM-42164 #comment Added setup instructions to README #time 30m #done"
```

### 8. Switch to `main` branch and merge changes
```bash
git checkout main
git merge development
```

### 9. Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/new-project.git
git push -u origin main
git push origin development
```

---

## ✅ Expected Outcome

- Branch `development` created successfully
- README.md includes all setup instructions
- Commits follow Smart Commit format
- Changes from `development` merged into `main`

---

## 🔗 Definition of Done (DoD)

Provide a link to your `README.md` in the `main` branch:

```
https://github.com/smaystr/new-project/blob/main/README.md
```
