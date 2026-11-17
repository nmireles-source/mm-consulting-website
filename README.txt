M&M Consulting Quarto Website Starter

1. Unzip into a folder.
2. Open the folder in RStudio (File > Open Project if you create an RStudio project in it), or run 'quarto preview' from its terminal.
3. Edit the .qmd content and _quarto.yml.
4. Run 'quarto render' to produce the docs/ directory.
5. Create a PUBLIC GitHub repository and push the entire project, including docs/ and .nojekyll.
6. Under GitHub repository Settings > Pages, choose Deploy from a branch, main, /docs.
7. When the default site works, set the custom domain in GitHub Pages settings FIRST.
8. Add GitHub Pages DNS A records and www CNAME at Porkbun. See GitHub's official custom domain documentation for current values.
9. Use 'quarto render' and push updated files whenever you edit.

The site includes placeholder names and contact info. Replace before publishing.
