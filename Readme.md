## Main Task : GitHub & GitLab Collaboration & workflow setup

### Part 1: GitHub Tasks

### Subtask 1: Repository Setup
```
Create two repositories on GitHub
 1. Private-repo
 2. Public-repo
```

![](pic%201.png)

### Subtask 2: Local Development
```
 Clone both repos on your local machine using HTTPS.
```
![](pic%202.png)
![](pic%203.png)
```
 In the private repo:
 Add a few files (e.g., index.html , readme.md ) and make at least two commits.
```
![](pic%204.png)
### Subtask 3: Collaboration Workflow
```
 On GitHub, create a Pull Request (PR) to merge dev into 
main 
```
![](pic%205.png)
```
Review and merge the PR.
```
![](pic%206.png)
```
 Verify that changes are reflected in the main branch after merging.
```

![](pic%207.png)


### Part 2: GitLab Tasks
### Subtask 4: GitLab Repository Setup

```
Create a private repository on GitLab.
```
![](pic%208.png)

```
Clone it on your local machine using SSH (not HTTPS).

NOTE :
to clone the private project we need access key
```
![](pic%2018.png)
![](pic%209.png)

```
Create a simple project structure (e.g., src/app.py , docs/guide.md ).
```
![](pic%2010.png)

### Subtask 5: Repository Mirroring

### Create a mirror setup:

```
Set the GitHub private repo as the mirror of your GitLab repo.
```
![](pic%2011.png)


### NOTE:
```
1. for this we need to create a repo on GitHub
```
![](pic%2012.png)
```
2. give the URL of repo

3. give the username of github acc

4. create personal access token

5. paste it instead of password while mirroring
```
![](pic%2013.png)
![](pic%2014.png)

```
Push some changes to GitLab and verify if the changes reflect in GitHub
automatically.
```
![](pic%2015.png)
![](pic%2016.png)

### Subtask 6: Access Control

```
Invite your friend to the GitLab private repository:

1. Assign them the Guest role initially, observe the access

2. Then change their role to Developer, and let them push one file.
```
![](pic%2017.png)
