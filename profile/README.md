# Triad Partners Web Animation Library

## Description

This is a repository dedicated to housing a collaborative library of web animations for Triad Partners. Created and maintained by our talented web development team, this repository aims to provide a reusable set of high-quality animations for various projects.

## Technologies

- GSAP
- HTML
- CSS
- JavaScript

## Features

- A wide range of animations including website transitions, button animations, loading screens, and more.
- Reusable code snippets for easy implementation across multiple projects.

## Contribution Guidelines

### Coding Standards

While there are no strict coding standards, contributors are encouraged to maintain a clean and organized codebase. Below are some best practices and conventions to consider:

- Use clear and descriptive variable names.
- Comment your code to explain what specific animations do.
- Include a `README.md` for complex animations to outline usage instructions.

### File and Folder Naming Conventions

- Use hyphens to separate words (e.g., `button-animation`).
- Use lowercase letters for all filenames and folder names.
- Be descriptive but concise in naming files and folders.
- Group related files into folders with descriptive names.
- Use a consistent structure for multi-file animations (e.g., `fade-transition/fade-transition.html`).
- Optionally, include version numbers in filenames for evolving animations (e.g., `button-animation-v1.html`).
- Always include the correct file extension for the file type.

#### Example Directory Structure

```plaintext
triad-animation-library/
|-- transitions/
|   |-- fade-transition/
|   |   |-- fade-transition.html
|   |   |-- fade-transition.css
|   |   |-- fade-transition.js
|   |   |-- README.md
|   |-- slide-transition/
|   |-- ...
|-- loaders/
|-- buttons/
|-- README.md
```

## Repository Configuration 

### 1. Create or Clone a Repository

-   If Starting a New Project:
    -   Create a new repository on GitHub under your organization. You can do this by going to your organization's page on GitHub, clicking "New repository," and following the prompts.
    -   Once created, you'll see a URL for the repository. Copy this URL.
      
-   If Working on an Existing Project:
    -   Clone the existing repository to your local machine using:
        ```
        git clone git@github.com:organization/repo-name.git
        ```
    -   Replace `git@github.com:organization/repo-name.git` with the SSH URL of the repository.

### 2. Set Up Local Repository

-   Navigate to your project directory in the command line:
    ```
        cd path/to/your/project
    ```

-   If you started a new project and haven't cloned, initialize a Git repository:
    ```
        git init
    ```

-   Add the remote repository (only if you started a new project):
    ```
        git remote add origin git@github.com:organization/repo-name.git
    ```

-   Verify the remote setup:
    ```
    git remote -v
    ```

### 3. Create and Checkout a New Branch

-   It's good practice to create a new branch for your changes:
    ```
        git checkout -b your-branch-name
    ```

### 4. Make Changes and Commit

-   Make changes to your files as needed.
-   Stage the changes for commit:

    ```
        git add .
    ```

-   Commit the changes with a message:

    ```
        git commit -m "Your commit message"
    ```

### 5. Push Changes to GitHub

-   Push your branch to the remote repository:

    ```
        git push origin your-branch-name
    ```


### Additional Notes:

-   Ensure your SSH keys are set up and linked to your GitHub account.

By following these steps, you can effectively push your code to an organization's GitHub repository. Remember to regularly pull changes from the remote repository to stay up-to-date with the team's work.
