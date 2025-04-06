# DevOps Documentation

## About the Project

Imagine a digital space where book lovers can connect and share their literary experiences. Our proposal is to create a **social network for books**, where each user can:

- **Follow their favorite books and authors**, receiving updates on new works and releases.
- **Leave detailed reviews** of the books they have read, helping other readers discover new stories.
- **Rate their favorite books**, providing valuable insights for others to decide whether to purchase a book.
- **Comment on reviews** and interact with fellow readers, forming a vibrant community passionate about literature.

Each user will have their own account, offering a personalized and unique experience where their preferences and readings are easily accessible. At this initial stage, we are focusing on creating a **CRUD for books**, allowing users to add and edit information about their favorite works.

## Project Settings

Each project repository must contain its specific settings in its **README** file.

## Programming Standards

We will use **GitFlow**, where:

- The **main** branch is designated for **production**.
- The **development** branch is designated for **staging**.

No development should be done directly in `main` or `development`. Every change must be made in a **separate branch**, and the merge must be performed via **Pull Request (PR)**.

## Branch Naming Convention

Branches must follow the structure:

- **For branches linked to an issue:**\
  **`<type>/[issue-id]/<description>`**
- **For branches without an issue reference:**\
  **`<type>/<description>`**

### Structure:

- **`<type>`** → Defines the branch purpose (e.g., `feature`, `bugfix`, `hotfix`, `release`, etc.).
- **`[issue-id]`** (optional) → Corresponding issue number in the management system (e.g., Jira, GitHub Issues).
- **`<description>`** → A short and descriptive name for the task.

### Allowed Branch Types:

- **`feature/`** → Feature branches
- **`release/`** → Release branches
- **`hotfix/`** → Hotfix branches
- **`bugfix/`** → Bugfix branches
- **`support/`** → Support branches
- **`<version>`** → Version tag prefix

## Pull Requests

- Every PR must have at least **one reviewer**.
- If applicable, the PR must follow the **template configured in the repository**.
- A sample PR template from [GitHub Pull Request Template](https://axolo.co/blog/p/part-3-github-pull-request-template) can be found in the **`.github`** folder under the name **`PULL_REQUEST_TEMPLATE.md`**.

## Commit Convention

We follow the **Conventional Commits** standard. The commit message format should be:

```
<type>[optional scope]: <description>

    [optional body]
    <issues references>
```

### Guidelines:

- The **body** is optional but should include issue numbers when relevant.
- If no description is needed, at least provide the issue numbers involved.

