# SAMCO Restaurants — Branches & Contact Website

A beautiful, optimized, mobile-responsive single-page website focusing on the branch contact details, locations, and directions for SAMCO Restaurants in Chennai. 

Serving Madras since 1962, this page serves as a dedicated quick-access portal for customers looking for specific branch phone numbers, emails, and direct Google Maps navigation.

---

## 📁 Project Structure

```text
samco-website-contact/
├── assets/
│   └── samco-logo.png    # Premium generated logo emblem
├── index.html            # Main markup file
├── style.css             # Vanilla CSS styling
├── vercel.json           # Vercel-specific deployment configuration (headers, caching)
└── .gitignore            # Git ignore rules
```

---

## 🚀 Local Development

To run this website locally, you can open `index.html` directly in your browser or run a local development server:

1. **Option A (VS Code Live Server)**:
   If you use VS Code, install the **Live Server** extension, then click the **Go Live** button in the bottom status bar.
   
2. **Option B (Python)**:
   If Python is installed, run this command in your terminal:
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your web browser.

3. **Option C (Node.js/npm)**:
   If Node.js is installed, you can use `serve` to launch a server:
   ```bash
   npx serve .
   ```

---

## 🛠️ How to Upload to GitHub

Follow these steps to initialize a Git repository and push your website code to GitHub:

1. **Initialize Git**:
   ```bash
   git init
   ```
2. **Add all files**:
   ```bash
   git add .
   ```
3. **Commit the changes**:
   ```bash
   git commit -m "initial commit: add SAMCO branch website files"
   ```
4. **Link to GitHub & Push**:
   Create a new blank repository on [GitHub](https://github.com/new). Then run the following commands (replace the URL with your repository URL):
   ```bash
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

---

## 🌐 Deploying to Vercel

### Option 1: Vercel Dashboard (Recommended)

1. Sign up or log into [Vercel](https://vercel.com).
2. Click **Add New** > **Project**.
3. Import your GitHub repository that you pushed in the previous step.
4. Click **Deploy**. Vercel will automatically host it and give you a live production URL! Every time you push updates to GitHub, Vercel will automatically redeploy it.

### Option 2: Vercel CLI (Direct command line deployment)

If you have Node.js and want to deploy directly from your terminal:

1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Log in to Vercel:
   ```bash
   vercel login
   ```
3. Deploy the project:
   ```bash
   vercel
   ```
   Follow the prompts. Once happy with the preview, deploy to production:
   ```bash
   vercel --prod
   ```
