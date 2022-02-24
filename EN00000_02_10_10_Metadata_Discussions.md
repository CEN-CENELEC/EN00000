WS 2 – Available Metadata on GitHub
===================================

***[Back to Start Page](EN00000_00_00_00_Start.md)***

This summary provides a brief overview of the metadata stored for GitHub
repositories. A description of the data and the corresponding API can be
found under the following link:

https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api

How to access the data?
-----------------------

The data can be accessed by the GitHub API.

### Examples:

1.  DIN-DKE OSS-Demonstrator

https://api.github.com/users/DIN-DKE/repos

1.  CEN/CENELEC OSS-Demonstrator

https://api.github.com/users/CEN-CENELEC/repos

As an example, the metadata of the first project of the
DIN-DKE-Demonstrator is listed below:


```


[
  {
    "id": 399396413,
    "node_id": "MDEwOlJlcG9zaXRvcnkzOTkzOTY0MTM=",
    "name": "DIN-DKE",
    "full_name": "DIN-DKE/DIN-DKE",
    "private": false,
    "owner": {
      "login": "DIN-DKE",
      "id": 89450610,
      "node_id": "MDQ6VXNlcjg5NDUwNjEw",
      "avatar_url": "https://avatars.githubusercontent.com/u/89450610?v=4",
      "gravatar_id": "",
      "url": "https://api.github.com/users/DIN-DKE",
      "html_url": "https://github.com/DIN-DKE",
      "followers_url": "https://api.github.com/users/DIN-DKE/followers",
      "following_url": "https://api.github.com/users/DIN-DKE/following{/other_user}",
      "gists_url": "https://api.github.com/users/DIN-DKE/gists{/gist_id}",
      "starred_url": "https://api.github.com/users/DIN-DKE/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/DIN-DKE/subscriptions",
      "organizations_url": "https://api.github.com/users/DIN-DKE/orgs",
      "repos_url": "https://api.github.com/users/DIN-DKE/repos",
      "events_url": "https://api.github.com/users/DIN-DKE/events{/privacy}",
      "received_events_url": "https://api.github.com/users/DIN-DKE/received_events",
      "type": "User",
      "site_admin": false
    },
    "html_url": "https://github.com/DIN-DKE/DIN-DKE",
    "description": "Config files for my GitHub profile.",
    "fork": false,
    "url": "https://api.github.com/repos/DIN-DKE/DIN-DKE",
    "forks_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/forks",
    "keys_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/keys{/key_id}",
    "collaborators_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/collaborators{/collaborator}",
    "teams_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/teams",
    "hooks_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/hooks",
    "issue_events_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/issues/events{/number}",
    "events_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/events",
    "assignees_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/assignees{/user}",
    "branches_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/branches{/branch}",
    "tags_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/tags",
    "blobs_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/git/blobs{/sha}",
    "git_tags_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/git/tags{/sha}",
    "git_refs_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/git/refs{/sha}",
    "trees_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/git/trees{/sha}",
    "statuses_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/statuses/{sha}",
    "languages_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/languages",
    "stargazers_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/stargazers",
    "contributors_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/contributors",
    "subscribers_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/subscribers",
    "subscription_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/subscription",
    "commits_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/commits{/sha}",
    "git_commits_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/git/commits{/sha}",
    "comments_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/comments{/number}",
    "issue_comment_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/issues/comments{/number}",
    "contents_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/contents/{+path}",
    "compare_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/compare/{base}...{head}",
    "merges_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/merges",
    "archive_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/{archive_format}{/ref}",
    "downloads_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/downloads",
    "issues_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/issues{/number}",
    "pulls_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/pulls{/number}",
    "milestones_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/milestones{/number}",
    "notifications_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/notifications{?since,all,participating}",
    "labels_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/labels{/name}",
    "releases_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/releases{/id}",
    "deployments_url": "https://api.github.com/repos/DIN-DKE/DIN-DKE/deployments",
    "created_at": "2021-08-24T08:49:37Z",
    "updated_at": "2021-09-21T07:56:23Z",
    "pushed_at": "2021-09-21T07:56:20Z",
    "git_url": "git://github.com/DIN-DKE/DIN-DKE.git",
    "ssh_url": "git@github.com:DIN-DKE/DIN-DKE.git",
    "clone_url": "https://github.com/DIN-DKE/DIN-DKE.git",
    "svn_url": "https://github.com/DIN-DKE/DIN-DKE",
    "homepage": "https://github.com/DIN-DKE",
    "size": 21,
    "stargazers_count": 0,
    "watchers_count": 0,
    "language": null,
    "has_issues": false,
    "has_projects": true,
    "has_downloads": true,
    "has_wiki": false,
    "has_pages": false,
    "forks_count": 0,
    "mirror_url": null,
    "archived": false,
    "disabled": false,
    "open_issues_count": 0,
    "license": null,
    "allow_forking": true,
    "is_template": false,
    "topics": [
      "config",
      "github-config"
    ],
    "visibility": "public",
    "forks": 0,
    "open_issues": 0,
    "watchers": 0,
    "default_branch": "main"
  },


 ...

]

```


What data are necessary?
------------------------

The discussion in WS 2 led to the discussion, that most project relevant
metadata should be hosted on CEN/CENELEC’s existing infrastructure.

This led to the decision that only a minimal data set should be stored
on GitHub. The following table shows the data that must be available to
initiate a project:

- package name mandatory Name of the software package.
- project title mandatory Project title, can vary from package name.
- version mandatory Current version.
- author name mandatory Author of the package.

> (It must be check if CEN/CENELEC as an organisation can be the
> author.)

- licence mandatory
- copyright mandatory
- created (at) mandatory (auto entry)
- published (at) optional First commit. (Created by github)
- description optional Scope

#### Discussion:

-   What additional data do the other workstreams need?
-   Legal Topic: GitHub expects an author of the software package.
    Usually this is an individual person, but can it be an organisation
    as CEN/CENELEC?
-   Governance Structures:

WS 2 proposes to host the data of the collaborators, users, etc. on
CEN/CENELEC systems and play them back to GitHub via the API.


***[Back to Start Page](EN00000_00_00_00_Start.md)***

