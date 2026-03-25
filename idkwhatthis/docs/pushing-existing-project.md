# Pushing an Existing Project to Github

## Overview

This section guides users through the process of pushing an existing local project to a GitHub repository for version control and collaboration.

## Steps

1. Open Your Project Folder
    - **Navigate** to your existing project directory on your computer.
2. Open a Terminal in the Project Directory
    - **Right-click** inside the folder and select Git Bash, or
    - **Open** Visual Studio Code and launch the terminal.

3. Initialize a Git Repository
    - **Run** the following command to start tracking your project with Git:

    ```git init
    ```

4. Check Repository Status (Optional)
    - **Verify** which files are untracked:

    ```git status
    ```

5. Stage All Files
    - **Add** all project files to staging:

    ```git add .
    ```

6. Commit the Files
    - **Save** the staged files with a message:

    ```git commit -m "Initial commit"
    ```

7. Create a New Repository on GitHub
    - Go to GitHub and **create** a new repository (do not initialize it with a README if you already have files locally).
8. Copy the Repository URL
    - From your GitHub repo page, **copy** the HTTPS URL (e.g., https://github.com/username/repo.git).

9. Add the Remote Repository
    - **Link** your local project to GitHub:

    ```git remote add origin https://github.com/username/repo.git
    ```

10. Verify Remote Connection (Optional)

    ```git remote -v
    ```

11. Push to GitHub
    - **Send** your code to the remote repository:

    ```git push -u origin main
    ```

    (Use master instead of main if your branch uses that name.)

12. Confirm Upload
    - **Refresh** your GitHub repository page to ensure all files have been uploaded successfully.
