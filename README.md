# Portfolio Deployment Guide

Your portfolio files are ready in `/Users/bitanbiswas/Downloads/portfolio`. 

To deploy this minimalist AI Engineer portfolio to GitHub Pages:

1. **Create a new repository on GitHub:**
   - Go to [GitHub](https://github.com/new).
   - Name it `bitanb1999.github.io` (this exact name maps to your root GitHub pages domain).
   - Keep it Public. Do not initialize with a README.

2. **Push your code from your terminal:**
   Open your terminal and run the following commands:
   ```bash
   cd /Users/bitanbiswas/Downloads/portfolio
   git init
   git add .
   git commit -m "Initial commit: Minimalist AI Engineer Portfolio"
   git branch -M main
   # Replace <YOUR_REPO_URL> with the clone URL of the repository you just created
   git remote add origin https://github.com/bitanb1999/bitanb1999.github.io.git
   git push -u origin main
   ```

3. **Verify:**
   - Once pushed, GitHub automatically builds and deploys repositories named `username.github.io`.
   - In a few minutes, your site will be live at `https://bitanb1999.github.io/`.
