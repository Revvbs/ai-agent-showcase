# 🚀 Setup Instructions

## Step 1: Create GitHub Repo

1. Buka https://github.com/new
2. Repository name: `ai-agent-showcase`
3. Description: `AI Agent Infrastructure - Autonomous Crypto Research & Trading System`
4. **Public** ✅
5. **JANGAN** centang "Add README" (udah ada)
6. Click "Create repository"

## Step 2: Push Code

```bash
cd ~/ai-agent-showcase

# Set git config (ganti dengan info lo)
git config user.name "Your Name"
git config user.email "mail.revvbs@gmail.com"

# Add remote (ganti 'yourusername' dengan GitHub username lo)
git remote add origin https://github.com/yourusername/ai-agent-showcase.git

# Push
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Buka repo settings: `https://github.com/yourusername/ai-agent-showcase/settings/pages`
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)**
4. Click **Save**
5. Tunggu 1-2 menit

## Step 4: Access Live Site

**URL:** `https://yourusername.github.io/ai-agent-showcase/`

Ganti `yourusername` dengan GitHub username lo.

## Step 5: Update README

Edit `README.md`, ganti:
- `yourusername` → GitHub username lo
- `@[your_username]` → Telegram username lo

```bash
cd ~/ai-agent-showcase
nano README.md  # atau vim/code
git add README.md
git commit -m "Update username"
git push
```

## 📝 What to Submit in Form

**GitHub / Demo URL:**
```
https://yourusername.github.io/ai-agent-showcase/
```

**Or:**
```
GitHub: https://github.com/yourusername/ai-agent-showcase
Live Demo: https://yourusername.github.io/ai-agent-showcase/
```

---

## ✅ What's Included

- ✅ Interactive architecture diagram (HTML/CSS)
- ✅ Professional README with metrics
- ✅ No sensitive data (API keys, strategies, etc)
- ✅ Clean, professional presentation
- ✅ GitHub Pages ready

## 🔒 Security Check

**NOT included:**
- ❌ API keys
- ❌ Trading strategies
- ❌ Private configs
- ❌ Wallet addresses
- ❌ Real transaction data

**Safe to share publicly!** ✅

---

## 🎨 Preview

Open `index.html` in browser to preview:
```bash
cd ~/ai-agent-showcase
python3 -m http.server 8000
# Open http://localhost:8000 in browser
```

---

**Need help?** Ping gue di chat!
