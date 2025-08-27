# Vinay Gupta — MBA Portfolio (Quarto)

1. Install Quarto: https://quarto.org/docs/download/  
2. Open a terminal in this folder and run:  
   ```bash
   quarto preview
   ```
3. Edit `.qmd` files. Replace `assets/portrait-placeholder.jpg` and `files/Vinay_Gupta_Resume.pdf`.
4. To publish on GitHub Pages, set `output-dir: docs` (already set), then:
   ```bash
   quarto render
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/vinay-mba-portfolio.git
   git push -u origin main
   ```
5. In the repo settings on GitHub → **Pages**, choose **Deploy from Branch** → **main** / **docs**.