## What is source control??

Source control (or version control) is a system that tracks changes to files, especially code, over time. It allows multiple people to collaborate, keeps a history of edits, and makes it easy to revert to previous versions if needed.
Key Features:
- Collaboration: Multiple users can work on the same project without overwriting each other’s changes.
- Change Tracking: Records what was changed, who changed it, and when.
- Reversion: You can roll back to earlier versions to fix bugs or undo mistakes.
- Branching and Merging: Developers can work on features in isolation (branches) and combine them later (merging).

## What is Git??

**Git** is a distributed version control system (VCS) that helps developers track changes in code, collaborate effectively, and manage project versions. It is widely used for software development and supports workflows for teams of all sizes.

### Why Git is More Famous:
1. **Distributed System:** Each user has a complete copy of the project history, enabling offline work and better redundancy.
2. **Speed:** Git performs operations like commits, branching, and merging quickly compared to older tools.
3. **Branching & Merging:** Its branching model is lightweight and flexible, allowing easy experimentation and collaboration.
4. **Open Source & Free:** Git is open-source, making it accessible to everyone without cost.
5. **Ecosystem:** Platforms like GitHub, GitLab, and Bitbucket enhance Git’s usability by adding hosting, collaboration tools, and CI/CD features.
6. **Community & Adoption:** Git has become the industry standard, meaning lots of learning resources, integrations, and community support.

## How Git and Github are used together?

Git and GitHub are closely related but serve different purposes:

### **Git**:
- **Purpose:** A tool for version control that runs locally on your computer.
- **Functionality:** Tracks changes, manages branches, commits, and merges.
- **Offline Capability:** Works without an internet connection.

### **GitHub**:
- **Purpose:** A cloud-based platform for hosting Git repositories.
- **Functionality:** Adds collaboration tools like pull requests, issue tracking, and code reviews. Also provides CI/CD, project boards, and discussions.
- **Remote Repositories:** Acts as a central hub to store and share Git repositories, enabling team collaboration and remote access.

### How They Work Together:
1. **Repository Hosting:**
    - Create a Git repository locally using Git (`git init`).
    - Push it to GitHub to make it accessible online.

2. **Collaboration:**
    - Multiple developers can clone a GitHub-hosted repository to their local machines.
    - Use Git commands (like `git pull` and `git push`) to synchronize local changes with the GitHub repository.

3. **Enhanced Workflow:**
    - GitHub adds features like pull requests for code reviews, branching for collaborative development, and action workflows for automation.

### Example Workflow:
1. **Local Development with Git:**
    - Use `git add`, `git commit`, and `git branch` to manage code versions.
2. **Push to GitHub:**
    - Use `git push origin main` to upload changes to a remote repository on GitHub.
3. **Collaborate:**
    - Team members use `git pull` to sync changes or create pull requests on GitHub for review.

# WORKING WITH GIT

* Initiate an empty git repository
- git init

* Define username and email address for git
- git config --global user.name "Awantika Chauhan"
- git config --global user.email "awantika@gmail.com"







