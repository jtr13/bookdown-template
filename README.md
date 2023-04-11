This is a template for creating an [HTML GitBook style](https://bookdown.org/yihui/bookdown/html.html#gitbook-style) **[bookdown](https://github.com/rstudio/bookdown)** book, [hosted on GitHub Pages](https://bookdown.org/yihui/bookdown/github.html). It is based on the one created with *File, New Project..., New Directory, Book Project using bookdown* in RStudio. It assumes you know how to use git/GitHub and R Markdown, and have some familiarity with the **bookdown** package. If you don't, the package author Yihue Xie's RStudio webinar *[Introduction to Bookdown (R Package)](https://www.youtube.com/watch?v=dVqVscgwSpw)* provides an excellent introduction. In addition, check out [*bookdown: Authoring Books and Technical Documents with R Markdown*](https://bookdown.org/yihui/bookdown), also by Yihui Xie, both for the content and the format--it is itself a **bookdown** book.
If you need help getting git/GitHub to work with RStudio see: [Happy Git and GitHub for the useR](https://happygitwithr.com/) by Jenny Bryan.


## ABSOLUTE ESSENTIALS

*If you have any difficulties or have feedback of any kind, please file an issue or communicate through [Discussions](https://github.com/jtr13/bookdown-template/discussions).*

### Copy this template (GitHub)

- [ ] 1. Click the green "Use this template" button above. DO NOT FORK THE REPO. Choose a descriptive name for your repo based on your content. (Unlike when you fork a repo, you get to choose the name. If you change your mind before you do any work, delete your new repo and start over.)

### Set up Pages (GitHub)

- [ ] 1. On the home page of your repo, click Settings. Click the "Pages" section on the left. In the **Build and Deployment** section, set **Source** to "Deploy from a branch" (Classic Pages experience) and **Branch** to **main** with **/docs** folder. Click Save. Above the **Build and Deployment** section, a box will appear with your book's URL. Copy the URL. (Note that sometimes there is a delay until your book actually appears at that URL. If it doesn't appear after a few minutes, make a change and commit it to trigger a GitHub Pages build.)	

- [ ] 2. Click the gear button near "About" on the home page of the repo and paste your book URL into the **Website** field that appears on the right.

### Copy the repo link (GitHub)

- [ ] 1. Click the green Code button and copy the link under HTTPS. It should have the format: `https://github.com/[USERNAME]/[REPO NAME].git`

### Clone the repo (RStudio)

- [ ] 1. Clone your new repo with *File, New Project..., Version Control, Git* in RStudio. You will need to paste the link from the previous step in the Repository URL box.

### Edit some key files (RStudio)

- [ ] 1. In `index.Rmd`, change YOUR TITLE HERE to your title.

- [ ] 2. In `index.Rmd`, change YOUR NAMES HERE to your names.

- [ ] 3. In `_bookdown.yml`, change YOUR GITHUB USERNAME to your GitHub username in the two places it appears.

- [ ] 4. In `_bookdown.yml`, change YOUR GITHUB REPO to your GitHub repo name in the two places it appears.

(Note that 3. and 4. provide links to the `.Rmd` files of your project for editing and viewing. If you move your `.Rmd` files you will need to update these file paths. Once your book is rendered, test that the edit (pen) and view (eye) buttons work.)

- [ ] 5. In `_output.yml`, change YOUR SHORT TITLE to a shortened version of your title. (Leave the "after:" line indicating that the book was published with bookdown as is.)

### Render the book (RStudio)

- [ ] 1. Install **bookdown** with `install.packages("bookdown")`. If you already have it, update to the most recent version.

- [ ] 2. Render locally with `bookdown::render_book("index.Rmd")` or clicking the *Build book* button which should appear in the Build tab (in the same pane as Environment, History, Connections, ...).

- [ ] 3. Use `browseURL("docs/index.html")` to view your book locally (or just open `index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)

### Edit README	(GitHub or RStudio)

Once you've completed these steps, delete the content of this **README** and add a short description of your project with a link to the book URL. It would be appreciated if you add the following to the end:	

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/bookdown-template.*

(And starring the repo would be nice too!)

### Demo Video

A demo video showing how to create a **bookdown book** following these instructions: http://bit.ly/fiveminutebookdown

### Additional features

Please consult the official guide to **bookdown**: https://bookdown.org/yihui/bookdown

