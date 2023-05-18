### Cloning this repository to your local computer with Rstudio

1.  In `RStudio`, go to \"File \> New Project\"

2.  Click on \"*Version Control: Checkout a project from a version control repository*\"

3.  Click on \"*Git: Clone a project from a repository*\"

4.  Fill in the info:

    -   URL: https://github.com/lukembrowne/CDD-appendix.git

    -   Create as a subdirectory of: Browse to where you would like to create this folder

### Cloning using command line

```{bash}
git clone https://github.com/lukembrowne/CDD-appendix.git
git pull
```

### General Workflow

-   Create an issue on Github for features / changes we'd like to see to the code
-   Each collaborator should create a new branch when they want to make changes or add new features. This can be done using the command: git checkout -b <branch-name>.
  - You can name the branch something related to the feature/code
-   They make changes to the files on their local system and commit the changes using git add . to add all the changes and git commit -m "<commit message>" to commit the changes.
-   After committing the changes, they push the branch to the remote repository using git push origin <branch-name>.
-   Then, they should open a Pull Request on Github. This is a request to merge the changes in their branch into the main branch.
-   The other collaborators review the changes and either approve or request changes. Once approved, the changes can be merged into the main branch.
-   After merging, the branch can be deleted both locally (git branch -d <branch-name>) and on the remote repository (git push origin --delete <branch-name>).



### Information about Quarto books

- [General info about Quarto books](https://quarto.org/docs/books/)
- [Book structure](https://quarto.org/docs/books/book-structure.html)
- [Cross referencing](https://quarto.org/docs/books/book-crossrefs.html)
- [Customizing book output](https://quarto.org/docs/books/book-output.html)
- [Book options](https://quarto.org/docs/reference/projects/books.html)

