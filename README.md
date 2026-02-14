# Instructions for Updating Wiki

## Setting Up

Download and install RStudio and R: https://cran.r-project.org/bin/macosx/.

**Render the book (RStudio)**

1. Install **bookdown** with `install.packages("bookdown")`. If you already have it, update to the most recent version.

- **Copy the repo link (GitHub):** Get the github reportiory link under HTTPS of the format: `https://github.com/[USERNAME]/[REPO NAME].git`
- **Clone the repo (RStudio):** Clone your new repo with *File, New Project..., Version Control, Git* in RStudio. Paste the link from the previous step in the Repository URL box.

2. Render locally with `bookdown::render_book("index.Rmd")` or clicking the *Build book* button which should appear in the Build tab (in the same pane as Environment, History, Connections, ...).

3. Use `browseURL("docs/index.html")` to view your book locally (or just open `index.html` in a browser).

4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)


## Editing Pages

Feel free to fix make minor changes.