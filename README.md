# stin-2024-cv

## Uciteluv repozitar
[https://github.com/roman-spanek/stin-2024-cv](https://github.com/roman-spanek/stin-2024-cv)

## Git manual

[https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init)

## Basic operations with git

#### Clone a repository using SSH
```bash
git clone git@gitlab.tul.cz:david.salek/stin.git
```

#### Adding files to be updated/uploaded
```bash
git add file
```

#### Removing files from repositary
```bash
git rm file
```

#### Committing changes
```bash
git commit -m "Commit comment"
```

#### Pushing to the repository
```bash
git push origin branch_name
```

#### Changing a branch
```bash
git branch -M branch_name
```

***

## Add your files
```
cd existing_repo
git remote add origin https://gitlab.tul.cz/stin-2024/stin-2024-cv.git
git branch -M main
git push -uf origin main
```

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Set auto-merge](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing (SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***