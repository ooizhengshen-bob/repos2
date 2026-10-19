#**Project Overview**

This repository is used for module-Applied Robotics and AI project for coursework 1. Now just finish the setup of the workspace to keep a history of changes and save the code on Github.


##**Coursework 1 requirement:**

Record a video that shows the following requirement.

1.Use Trello to do project management 

2.Create GitHub Repo

3.Show Add, Commit and Push

4.Create and use branches

5.Create Clone 

**Project board (Trello):**

This is the link to join my Trello for project management: 
[my Trello board](https://trello.com/b/3Lxj38Of/applied-robotics-ai-project)

- **Lists:** I put To Do, In Progress, Done
- **Labels:** show the type of task
- **Due dates:** set a deadline 
- **Lecturer:** invited Ms Sarina to the Trello

## 1. Setup 

These steps only need to do once. (unless you changed another computer)

**Tell Git who I am** :

```bash
git config --global user.name "Ooi Zheng Shen"
git config --global user.email "my-github-email@example.com"
```

**Start a new repository and link it to GitHub:**

```bash
git init                      # start git in your project folder
git add .                     # here we use hello.txt 
git commit -m "first commit"  # save a snapshot to your computer
git branch -M main            # name the main branch as "main". For every new task or want to change something, making a new branch so main didn't be affected.
git remote add origin https://github.com/ooizhengshen-bob/repos2.git # put your repository link 
git push -u origin main       # upload to GitHub
```

**Here to get a copy of the repository on another computer:**

```bash
git clone https://github.com/ooizhengshen-bob/repos2.git
```

## 2. Daily workflow: Add, Commit, Push

### Step 1: Basic Add, Commit, Push
```bash
git add hello.txt                       # add the file we created inside the folder
git commit -m "first commit"            # give a name
git push                                # upload to Github
```

### Step 2: Change hello.txt

``` bash
gid add hello.txt                       # add the changed file again
git commit -m "modified hello.txt"      # save a snapshot 
git push -u origin main                 # upload to github
```

## 3. Clone

Download a copy of the repository from Github

```bash
git clone https://github.com/ooizhengshen-bob/repos2.git
```

---



