# INT150 Web Tech Classwork Instruction

Written by: Olarn Rojanapornpun  
Last update: 24 March 2025


## Working on your repository
1. Use the repository created when you accept `classwork` assignment.
2. Organize your work so that each lab work is stored under different directory.
3. Create `index.html` at the root of your repository as an index to each lab work. This index file must contains link to each lab work, you may use relative path for each link.
4. You should create a branch for each lab work and merge it to `main` branch when it is completed. (Use `github` flow, which will be covered in class 09)


## Migrate your personal repository
1. If you have existing INT150 repository, it is best to migrate it to `classwork` assignment repository so that commit history is carried forward.
2. Under your INT150 repository, change the remote repository URL to `classwork` assignment repository with `git remote set-url origin <<classwork-assignment-repo-url>>`
3. Push all of your branches with `git push origin --all` to `classwork` assignment repository.  

Additional info: https://www.atlassian.com/git/tutorials/git-move-repository


## Deployment
1. Deploy your work on `st-apps01.sit.kmutt.ac.th` under `~/html/int150`
2. Your work can be viewed at `https://int150.sit.kmutt.ac.th/<xxxxx>/int150` where `<xxxxx>` is your private nested path. For example, `lab01` work can be viewed at `https://int150.sit.kmutt.ac.th/<xxxxx>/int150/lab01`
3. Use `git pull` to pull latest commit on your `classwork` repository in `INT150-2024` classroom.

**Important** : Do not share your `st-apps01` account password and your URL to anyone!