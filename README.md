# Rowan K. O'Hara

Hello, I am a first-generation Master's student studying Bioinformatics at Virginia Commonwealth University.
I built this site so that you may get to know a little about me and my research quickly.
Please [reach out](mailto:oharark@vcu.edu) if you have any questions.

## How I Built the Site

This site is built utilizing [Quarto](https://quarto.org/docs/websites/) and published with [GitHub Pages](https://quarto.org/docs/publishing/github-pages.html).

- First, I created a new project in RStudio and chose **Quarto Website**.
   
   > Quarto handles most of html and JavaScript to actually build the website. You just need to build each page of your website by creating a `.qmd` file for it and tell Quarto to render them in the `_quarto.yml` file.

- This should be connected to a GitHUb repository, and if you want this to be a personal site, use the `username.github.io` name.
- Then, I used the `quarto publish gh-pages` command in the terminal tab in RStudio.
- I created a `gh-pages` branch to work on and set the Pages setting to "**Deploy from source branch**" to `gh-pages`.
- Done! Just continue editing, commiting the changes, and pushing to GitHub.
  - Use the command `quarto preview` to render and preview your changes before pushing them.
  
## Helpful Resources
This was my firrst attempt creating a website, and I knew nothing of Quarto or HTML. I found these resources to be helpful:
- [Quarto documentation](https://quarto.org/docs/websites/)
- [GitHub documentation](https://quarto.org/docs/publishing/github-pages.html)
- [Thomas Mock's intro](https://rstudio-conf-2022.github.io/get-started-quarto/)
- [Andrew Heiss' example site](https://github.com/andrewheiss/nonprofitf22.classes.andrewheiss.com)

`
