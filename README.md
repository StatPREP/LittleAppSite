---
title: "Little App Activities source materials"
---

## Instructions

1. All activity documents are in the `_posts/Activities` directory.
2. Each activity is a subdirectory of `_posts/Activities`.
3. To create a new activity, copy this `Generic` activity directory (or any other) and save the copy under a new name in `_posts/Activities`.
4. Edit the `activity.Rmd` file so that it describes your activity.
    a. Make sure give an appropriate title on after the `title:` header in  the YAML metadata at the top of the file. This will be the title of the PDF and Word formats of your activity.
    b. When  you are  satisfied, "knit" the  `activity.Rmd` file to both Word and PDF formats.
5. **There is another file to edit.** Edit the `home_page.Rmd` document. 
    a. Give the title you  want to  appear for the activity on this web site. 
    b. Modify the description field as a quick guide to people who view the site.
    c. Leave everything else alone. (But  follow the DELETE instructions above,  do get rid of these instructions.)
6. **KNIT** the  `home_page.Rmd` document.  It will seem like it fails, but everything  is OK.
7. Edit the `Activities.Rmd` file in the top  level of this project to add your activity to the gallery.
8. Go to the "Build" tab in RStudio and press "Build Website."
9. State, commit, pull, and push the repository to GitHub.


