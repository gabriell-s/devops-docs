# devops-docs

Regarding the settings for each project:
The settings for each project repository must be in their README.

Regarding programming standards:
We will use gitflow where we have the main branch which would be for production and the development branch which would be for staging.
No development should be done directly in main or directly in development, it must have its own branch and the merge must be done via PR (Pull Request).

## Branch

Branches must be named following the structure **<type>/[issue-id]/<description>**. For branches without issue, just use **<type>/<description>**
A branch deve ser nomeada seguindo a estrutura <type>/[issue-id]/<description> para branch sem um issue de referencia pode ser utilizado <type>/<description>.


* <type> → Defines the branch purpose (feature, bugfix, hotfix, release, etc.).
* [issue-id] (optional) → Number issue in the management system (Jira, GitHub Issues, etc.).
* <description> → A short and descriptive name for the task.

The types are:
[feature/]: To Feature branches
[release/]: To Release branches
[hotfix/]: To Hotfix branches
[bugfix/]: To Bugfix branches
[support/]: To Support branches
[]: To Version tag prefix

## Pull request

The PR must have at least 1 (one) reviewer and if exists must follow the template configured in each repository.
One sample collected from [GitHub pull request template](https://axolo.co/blog/p/part-3-github-pull-request-template) can be found in the **.github** folder with 
PULL_REQUEST_TEMPLATE.md (link)[.github/PULL_REQUEST_TEMPLATE.md] name.


## Commit
For the commits we will use the convencional commits.
'''
<type>[optional scope]: <description>

    [optional body]<issues references>

'''
Although the body is optional, it is interesting to put the numbers of the issues involved inside it. If don't want describe, just put the numbers of issues involved.

