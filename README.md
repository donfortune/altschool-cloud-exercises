# AltSchool Cloud Exercises

Welcome to the AltSchool Cloud Exercises repository! This repository contains exercises and solutions.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository is a collection of cloud computing exercises designed for learning and practicing various cloud-related concepts. Whether you are a beginner or an experienced cloud engineer, you'll find exercises that cover a range of topics.

## Exercises

- **Exercise 1: [Title]**
  - Description: Brief description of the exercise.
  - Files: List of relevant files.
  - Instructions: Step-by-step instructions to complete the exercise.
  - Solution: Link to the solution or reference solution folder.

- **Exercise 2: Linux Commands Research**
  - **Task:** Find and document 10 new Linux commands beyond those covered in this module. Create a `commands.md` file with brief explanations, usage examples, and screenshots for each command.

  - **Submission:**
    - In the `exercise-2` directory, create a folder named `linux-commands`.
    - Inside `linux-commands`, add a `commands.md` file documenting the researched commands.
    
  - **Structure:**
    ```
    exercise-2/
    └── linux-commands/
        └── commands.md
    ```

  - **Tips:**
    - Keep descriptions concise.
    - Include examples and screenshots.
    - Ensure clarity in your documentation.

- **Exercise 3: User Groups and Permissions**
  - **Task:**
    - Create three groups: `admin`, `support`, and `engineering`.
    - Add the `admin` group to sudoers.
    - Create a user in each group.
    - Generate SSH keys for the user in the `admin` group.

  - **Submission:**
    - Submit the contents of the following files using the given format:
      - `/etc/passwd`
      - `/etc/group`
      - `/etc/sudoers`

  - **Tips:**
    - Clearly separate and label content for each file.
    - Ensure the format matches the example provided.

- **Exercise 4: Installing PHP 7.4**
  - **Task:**
    - Install PHP 7.4 on your local Linux machine using the `ppa:ondrej/php` package repository.
  
  - **Instructions:**
    - Learn how to use the `add-apt-repository` command.
    - Submit the content of `/etc/apt/sources.list`.
    - Provide the output of the `php -v` command.

  - **Tips:**
    - Clearly label and organize your submission files.
    - Verify the successful installation of PHP 7.4 using the `php -v` command.
   
- **Exercise 5: GitLab Setup and Git Configuration**
  - **Task:**
    - If not already done, set up a GitLab account.
    - Clone your existing `altschool-cloud-exercises` project to your local system.
    - Configure your name and email in Git's global configuration.

  - **Instructions:**
    - Ensure you have a GitHub account.
    - If you don't have a GitLab account, set one up.
    - Clone your existing `altschool-cloud-exercises` project to your local system.
    - Configure your name and email using Git's global config.
  
  - **Submission:**
    - Submit the output of the following commands:
      - `git config -l`
      - `git remote -v`
      - `git log`

  - **Tips:**
    - Ensure that the GitLab setup and cloning process are clearly documented.
    - Verify the correctness of your Git configurations.
    - Submit outputs in separate files for clarity.




Feel free to explore the exercises and enhance your cloud skills!

## Getting Started

To get started with the exercises, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/altschool-cloud-exercises.git
