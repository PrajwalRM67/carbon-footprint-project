# 🌱 EcoTwin AI — Carbon Footprint Intelligence Platform

> **Campus Carbon Accounting & Digital Twin Simulation Platform**  
> Combining Computer Vision, Digital Twin simulations, and Generative AI for verified carbon accounting across college campuses.

---

## 📋 Overview

**EcoTwin AI** is a state-of-the-art sustainability and carbon intelligence dashboard designed for educational institutions and university campuses. It provides actionable insights into campus emissions, energy usage, mobility footprint, and automated mitigation planning.

### ✨ Key Features
- **🌐 Real-Time Campus Digital Twin**: Visualizes building energy, mobility footprint, solar generation, and campus zones in real time.
- **📊 Carbon Accounting (Scope 1, 2 & 3)**: Unified telemetry for electricity grid demand, transit emissions, and waste metrics.
- **🤖 EcoTwin AI Strategic Copilot**: Interactive generative AI assistant offering mitigation suggestions, policy recommendations, and scenario simulations.
- **📈 Interactive Analytics & Projections**: Dynamic charts for tracking net-zero milestones and seasonal trends.
- **⚡ Fully Self-Contained Frontend**: Modern React single-page application with responsive dark theme, Tailwind CSS, Lucide icons, and zero backend dependencies required for client-side evaluation.

---

## 🚀 How to Run Locally

You can run this project locally without any installation or complicated setup:

### Option 1: Direct File Opening
Double-click `index.html` or right-click and open it in any modern browser (Chrome, Edge, Firefox, Brave, Safari).

### Option 2: Using Python (Recommended)
If you have Python installed, open terminal or Command Prompt in this folder and run:
```bash
python -m http.server 3000
```
Then open [http://keen-speculoos-0bb8ce.netlify.app/) in your browser.

### Option 3: Using Node / NPX
If you have Node.js installed:
```bash
npx serve .
```

---

## 📤 How to Upload this Project to GitHub

Follow any of the methods below to upload this project to your GitHub account:

### Method 1: Uploading via GitHub Web (Simplest — No Git install needed)
1. Log in to [GitHub](https://github.com/) and click **New repository** (or click the `+` icon at the top right).
2. Name the repository `carbon-footprint` (or any name you prefer), keep it Public or Private, and leave "Add a README" **unchecked**. Click **Create repository**.
3. On the repository page, click the link that says **"uploading an existing file"**.
4. Drag and drop all the files and folders from `D:\carbon footprint` into the browser window:
   - `index.html`
   - `favicon.ico`
   - `package.json`
   - `.gitignore`
   - `README.md`
   - `assets/` folder
5. Enter a commit message like `Initial commit: EcoTwin AI platform` and click **Commit changes**.

---

### Method 2: Using GitHub Desktop (GUI)
1. Download and install [GitHub Desktop](https://desktop.github.com/) if you haven't already.
2. Open GitHub Desktop and sign in with your GitHub account.
3. Click **File > Add Local Repository** (or press `Ctrl + O`).
4. Choose the path: `D:\carbon footprint`.
5. If prompted that this directory is not a Git repository, click **"create a repository"**.
6. Click **Publish repository** to push it to your GitHub account.

---

### Method 3: Using Git Command Line (CLI)
If you have Git installed, open PowerShell or Command Prompt in `D:\carbon footprint`:

```bash
cd "D:\carbon footprint"

# Initialize Git repository
git init -b main

# Stage all files
git add .

# Create initial commit
git commit -m "feat: initial commit of EcoTwin AI carbon footprint platform"

# Link to your newly created GitHub repository (replace with your repo URL)
git remote add origin https://github.com/<YOUR_USERNAME>/carbon-footprint.git

# Push to GitHub
git push -u origin main
```

---

## 🌐 Deploying Live to GitHub Pages (Free Hosting)

Once uploaded to GitHub, you can host it live as a free website:
1. In your GitHub repository, go to **Settings > Pages** (in the left sidebar).
2. Under **Build and deployment > Source**, select **GitHub Actions** (or select **Deploy from a branch**, choose `main` branch, `/ (root)` folder, and click **Save**).
3. Within 1-2 minutes, GitHub will give you a live URL (e.g. `https://<YOUR_USERNAME>.github.io/carbon-footprint/`).

---

## 📁 Repository Structure

```
D:\carbon footprint\
│
├── index.html                   # Main application entry point
├── favicon.ico                  # Platform icon
├── package.json                 # Project metadata & npm runner scripts
├── .gitignore                   # Git ignore configuration
├── README.md                    # Project documentation & upload guide
│
├── .github/
│   └── workflows/
│       └── deploy.yml           # Automated GitHub Pages deployment workflow
│
└── assets/
    ├── index-CzMX8cnp.css       # Complete Tailwind CSS stylesheet
    └── index-D2Wdr_Tx.js        # Self-contained React application bundle
```

---

## 📜 Source Reference
- Preserved from deployed instance: [http://keen-speculoos-0bb8ce.netlify.app/](http://keen-speculoos-0bb8ce.netlify.app/)
- Platform: EcoTwin AI
- web Main Link - http://keen-speculoos-0bb8ce.netlify.app/
