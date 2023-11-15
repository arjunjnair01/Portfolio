+++
title = 'Task-02'
date = 2023-11-14T03:01:37+05:30

[cover]
  image = "amfoss.png"
  alt = "What is bioinformatics?"
  caption = ""
  relative = true

showtoc = true
draft = false
+++


# Lessgo Hugo


## How i approched the task:

This was an interesting but also a confusing task.I faced many issues on my way, but was able to solve somehow, definitely with the help og google. Nevertheless, i was happy to see the result.

Here are the steps i followed to complete the task:

### Step 1:
- I installed hugo using the terminal command 
> snap install hugo
- Meanwhile i also selected the theme i'll be using to build my portfolio.

### Step 2:
- Created a directory for the portfolio
> hugo new site portfolio

### Step 3:
- Moved into the portfolio dir.
- Clone the repository of the theme from hugo into this folder.
> git clone https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --depth=1
- I chose the **PaperMod** theme from hugo.
- Add **theme='PaperMod'** inside the *hugo.toml* file

### Step 4:
- Adding necessary changes to hugo.toml to create changes in the portfolio.
- Adding required photos and contents for the Portfolio.

### Step 5:
- Now to deploy the website in Github Pages, created a public repository **arjunjnair01.github.io**.
- Cloned the repository.

### Step 6:
- The command given below will create a new folder public inside the portfolio folder
> hugo -t PaperMod
- Now copy the contents of this public folder into our public repo cloned earlier.
> cp -a public/* ../arjunjnair01.github.io
- cd into the public repo.
- git add .
- git commit -m "Initial commit"
- git push -u origin main

### Step 7:
- Logged into my github account. Select the repo and in settings there will be **pages** under **code and automation** section.
- Select main from the drop down menu under *Build and deployment -> Branch*
- After few minutes the link to the site will be shown.

### Step 8:
- Pushed the portfolio repository.
- Wrote this blog.
- In the README.md in the task-02 folder, added the link to the site aswell as the portfolio repository.

I took help of several Youtube Videos as well as blogs to finish this task. Overall it was a new experience that would be helpfull to create beautiful websites without writing code from scratch, saving a lot of time and efforts.
