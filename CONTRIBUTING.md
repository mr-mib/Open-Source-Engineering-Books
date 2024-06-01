# Importance of CONTRIBUTING.md

Thank you for considering contributing to the Open Source Engineering Books repository! Your involvement is vital to the success of this project.

The `CONTRIBUTING.md` guides contributors on how to participate in the project. It explains the process of forking, creating a branch, submitting a pull request, and adhering to naming conventions for files and folders to ensure smooth collaboration.

## Contribution Guide

1. Fork this repository by clicking the "Fork" button at the top right of this page.

You will see the Open-Source-Engineering-Books folder into your repositories

2. Clone your fork locally:

   ```bash
   git clone https://github.com/your-username/Open-Source-Engineering-Books.git

3. Change directory to the one you just clone
   ```bash
   cd Open-Source-Engineering-Books

4. Create and switch to a new branch for your contribution:
   ```bash
   git checkout -b add-new-book

5. Add your PDF files to the appropriate folders or create one following these naming conventions:
   ```markdown
   - NAMING CONVENTION OF A FOLDER: lowercase-and-dash-between-each-word
   - NAMING CONVENTION OF A BOOK: Title-Author(s)-other-information
   ```

6. Go to [contributors](contributors.md) and make sure you follow the instructions. If you do so, we will be able to tag you on our social media post.

7. Save the file, commit your changes and push them to your fork. 

Make sure to change `book-title` and `name-folder`. If the title of the book is too long, please find a way to explicitly let us know which book you have added.

```bash
git add .

git commit -m "Add 'book-title' to the 'name-folder' folder"

git push
```

8. Submit a Pull Request
- Go to the github page at your fork and click on "Compare & pull request".
- Submit your pull request for review.