# Pair Programming with GitHub

Pair programming requires the transfer of code between the Driver and the Navigator. To facilitate this process in a remote environment we have chosen to use GitHub. This is a great opportunity to practice git commands.

### What is git?
Git is a software that allows you to keep track of your code history. GitHub is an online platform that uses git technology.

### What is GitHub?
GitHub allows developers to store their code and collaborate on projects.

There are many online git platforms that are used by development teams such as GitLab or Bitbucket. GitHub is the largest host of source code in the world with over 40 million users and 100 million repositories.

### What is a repository?
A repository (or repo) is basically a bucket to store a project. When it is on your GitHub it is a named storage place, when it is on your local machine, it looks like a directory.

### What is a README?
GitHub uses a particular file called a README to store instructions or information about a project or repo. READMEs are written in a language called markdown which is denoted with the file extension .md (short for markdown). Markdown is a language that writes and reads like normal text with a couple special shortcuts and tools that allow you to embed code snippets and links.

### How do we interact with GitHub?
On the command line! Yay!
There are three commands that you should know:

$ git add .
$ git commit -m "message about what you are doing"
$ git push origin master

These commands "push" the code you have you your local machine up to the GitHub repository.

When the next driver is ready:

$ git pull origin master

### Challenge

#### Step 1
- The Driver should navigate to an appropriate location on your machine
- Clone this directory
- $ git clone filepath
- cd into the directory
- Create a new markdown file using the command "touch"
- Name the file after your pair or team (for example: sarah-rachael.md)
- Remember, no spaces in the file name!
- Open the directory into a text editor
- Open the file you created and add some content - whatever you want
- View you markdown with control-shift-m
- Save the file
- In terminal, ensure you are in the correct directory
- $ git add .
- $ git commit -m "our first commit"
- $ git push origin master
- Switch roles

#### Step 2
- The new Driver should navigate to an appropriate location on your machine
- Clone this directory
- cd into the directory
- Open the directory into a text editor
- Make changes to the markdown file
- In terminal, ensure you are in the correct directory
- $ git add .
- $ git commit -m "description of changes"
- $ git push origin master
- Switch roles

### Step 3
- The new Driver should ensure they are in the correct directory
- $ git pull origin master
- Make changes to the markdown file
- In terminal, ensure you are in the correct directory
- $ git add .
- $ git commit -m "description of changes"
- $ git push origin master
- Switch roles

### Step 4
- Repeat Step 3

### Step 5
- Repeat Step 3

### Step 6
- Repeat Step 3
