# Aroma Mean Webpage Project

## Overview
A static webpage for "Aroma Mean - Aroma Leader Level 2 Certification Course". The project consists of a single-page layout with assets, modern typography, and a nature-inspired aesthetic.

## Current Project State
- `index.html`: Main content, internal styles, and layout.
- `aromamean/`: Folder containing images and brand assets.
- `main.js`: Empty script file (placeholder).
- `style.css`: Empty style file (placeholder).
- `GEMINI.md`: AI development guidelines.
- `.idx/`: Project configuration for Firebase Studio/IDX.

## Deployment Plan: Cloudflare Pages

### Step 1: Git Repository Preparation
- Ensure all project files, including images in `aromamean/`, are tracked and committed to the local git repository.
- Create a `.gitignore` to exclude unnecessary files (like logs).

### Step 2: Deployment Strategy
I will offer two options for deployment:

#### Option A: Git Integration (Recommended for CI/CD)
1. Push the local repository to a remote host (GitHub, GitLab, or Bitbucket).
2. Connect the remote repository to Cloudflare Pages via the Cloudflare Dashboard.
3. Cloudflare will automatically deploy on every push.

#### Option B: Direct CLI Deployment (Wrangler)
1. Use the Cloudflare `wrangler` CLI to deploy the project directly from the local environment.
2. This is useful for quick previews or if a remote git host is not preferred.

---

## Action Steps (Current Phase)

1. [ ] **Git Setup**: Add and commit all files to the local repository.
2. [ ] **Wrangler Deployment**: Guide the user through the `npx wrangler pages deploy` process for immediate deployment.
3. [ ] **GitHub Setup (Optional)**: Provide guidance on pushing to GitHub for automated deployments.
