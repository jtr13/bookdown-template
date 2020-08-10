This is a template for the EDAV final project. It is based on the template created with *File, New Project..., New Directory, Book Project using bookdown* in RStudio. 


## ABSOLUTE ESSENTIALS

*Follow these instructions and you will have a published bookdown book in less than five minutes. If you have any difficulties or have feedback of any kind, please file an issue.*

### Copy this template

- [ ] 1. Click the green "Use this template" button above.  DO NOT FORK THE REPO.

- [ ] 2. Choose a descriptive name for your repo, such as "federalbudget" or "AIDSdeaths".  (If you change your mind before you do any work, delete your new repo and start over.)

- [ ] 3. In the Description field, write: "Bookdown source files for EDAV final project".

### Clone the repo

- [ ] 1. Clone your new repo with *File, New Project..., Version Control, Git* in RStudio.

### Edit some key files

- [ ] 1. In `index.Rmd`, change YOUR TITLE HERE to your title.

- [ ] 2. In `index.Rmd`, change YOUR NAMES HERE to your names.

- [ ] 3. In `_bookdown.yml`, change YOUR GITHUB USERNAME to your GitHub username in the two places it appears.

- [ ] 4. In `_bookdown.yml`, change YOUR GITHUB REPO to your GitHub repo name in the two places it appears.

(Note that 3. and 4. provide links to the `.Rmd` files of your project for editing and viewing. If you move your `.Rmd` files you will need to update these file paths. Once your book is rendered, test that the edit (pen) and view (eye) buttons work.)

- [ ] 5. In `_output.yml`, change YOUR SHORT TITLE to a shortened version of your title. (Leave the "after:" line indicating that the book was published with bookdown as is.)

### Render the book

- [ ] 1. Install **bookdown** with `install.packages("bookdown")`. If you already have it, update to version 0.16 (2019-11-22).

- [ ] 2. Render locally with `bookdown::render_book("index.Rmd")`.

- [ ] 3. Use `browseURL("docs/index.html")` to view your book locally (or just open `index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)

### Set up GitHub Pages

- [ ] 1. On the home page of your repo, click Settings. Scroll down to the GitHub pages section and change **Source** to **master branch /docs folder**.  Above the **Source** line, a bar will appear with your book's URL. The bar will initially be blue and indicate that your book is *ready* to be published and will change to green once it is published. Copy the URL. (Note that sometimes there is a delay until your book actually appears at that URL. If it doesn't appear after a few minutes, try making a small change locally, rendering the book, and pushing the changes to trigger a deploy.)

- [ ] 2. Click the gear button near "About" on the home page of the repo and paste your book URL into the **Website** field that appears on the right.

At some point before you turn in your project, delete the content of this **README** and add a short description of your project with a link to the book URL. Please add: "This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVproject" to the end of the README.

For additional features, consult the official guide to **bookdown**: https://bookdown.org/yihui/bookdown



