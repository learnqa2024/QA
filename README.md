# What is Git?

Git is a **version control system** created by Linus Torvalds in 2005, maintained by Junio Hamano. It allows developers to:

- Track code changes.
- Identify who made changes.
- Collaborate on projects.

## What Git Does

1. **Repositories:** Organize and manage projects.
2. **Clone:** Work on a local copy of a project.
3. **Staging & Committing:** Track and save file changes.
4. **Branching & Merging:** Simultaneously manage different project versions.
5. **Pull & Push:** Sync local and remote repositories.

## How Git Works

1. **Initialize Git:** Turn a folder into a Git repository.
2. **Track Changes:** Monitor added, modified, or deleted files.
3. **Stage Changes:** Select files to prepare for a commit.
4. **Commit:** Save a snapshot of staged files.
5. **History & Reversion:** View all commits and revert to previous states.

Git uses a smart system to store changes (not full copies of files), optimizing storage and performance.

## Why Git?

- Over 70% of developers use Git.
- Enables global collaboration.
- Tracks full project history.
- Allows reversion to earlier project states.

# What is GitHub?

GitHub is a platform that uses Git to:

- Host source code (world's largest since 2018).
- Provide collaboration tools for developers.

> **Note:** Git and GitHub are different! Git is the tool; GitHub enhances its use.

We will focus on using Git with GitHub.

# Installing Git

You can download Git for free from the official website:

[🔗 Git Official Website](https://www.git-scm.com/)

## Using Git with the Command Line

To start using Git, open a command shell:

- **Windows:** Use Git Bash (included with Git for Windows).
- **Mac/Linux:** Use the built-in Terminal.

### Check if Git is Installed

Verify that Git is installed and working properly by running:

```bash
git --version
```

If Git is installed, you’ll see the installed version number, such as:

```
git version 2.42.0
```

# Configuring Git

Before using Git, configure it with your name and email. This ensures all commits are associated with your identity.

### Set Your Username and Email

Run the following commands in your terminal:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Replace `"Your Name"` and `"your-email@example.com"` with your actual name and email address.

> **Tip:** You’ll use this email when registering for GitHub later on.

### Why Configure Git?

- Ensures all commits are associated with your identity.
- Matches your details with services like GitHub or GitLab.

### Check Your Configuration

Verify your settings by running:

```bash
git config --global --list
```

You’ll see output similar to:

```
user.name=Your Name  
user.email=your-email@example.com
```

This confirms that Git is properly configured.
