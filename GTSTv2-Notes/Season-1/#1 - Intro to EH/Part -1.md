# What you have to know:

1. You don't hack because you know hacking concepts: You have to be practical! We learn both conceptual and practical parts, but if you skip the practical parts, Sorry for you.
2. You don't be a hacker in 1 night or with this class notes only! it's a slow and a patient path in which you will learn a lot through out your whole journey.
3. Don't be afraid to learn new things! Just stick to it and it will make sense someday.
4. Try to simplify everything, don't make them hard. Ask when you don't understand stuff.
5. It's not always sunshine, sometimes it doesn't make any sense.
6. Things that seems useless have purpose.
7. Daily learning mindset: This field, needs an everyday learning mindset, even after you become good on it, Reading Have to be your habit.
8. “Teacher can open the door, but you must enter it yourself”: Not only learning, also focus on practice, understanding each concept and staying curious.

### What the course have to promise…

- If you follow each step in this course.
- If you ask when you didn't understand,
- If you do exercise and actively engage on the course then:
    - You will be a Junior Hacker/Penetration Tester when the course ends.

### Prerequisites for this course:

- Passion
- Discipline > Motivation
- Curiosity
- Hackers mindset (thinking outside the box) = it's built overtime with experience
- Computer
- Internet
- Effective note-keeping

### GIT & GITHUB

- Git is a version control system or tool
- Simply, a tool to manage changes on your files version
- Saves the file locally or remotely server (github/gitlab)
- Made by the Linux development community.
- GitHub is a website/server which your git files are hosted on.
- Your files will be stored in folder called “Repository”.

### COMMON TERMS ON GIT

- Push: s an Action done when user try to upload his data to the remote GIT Server (GitHub/GitLab/Gogs). Which is basically uploading new data to your GitHub.
- Pull: is an action done when user try to download some changes and integrate to the previous Local Repo. Which is basically like updating or upgrading the current version of something.
- Clone: is an action done when user try to download a new repo. Which is basically downloading new files from another GitHub repo or any other place.
- Commit: a fundamental operation that saves your changes to the repo, allowing you to maintain a history of your project. Each commit is identified by a unique random string. Which is basically saving the changes that you've done on your GitHub repo or even a place where the changes that you've done are stored.
- Add: the process of staging changes in your working directory to be included in the next commit. Which means telling the GitHub repo that you've add some changes to your repo or git file.
- The work flow between these terms is like the following:-
    - You create a PROJECT and then ADD it to COMMIT and PUSH it to GitHub. Then when you want to edit this PROJECT, you PULL it and then edit it. The cycle keeps going on.
    - PROJECT -> ADD -> COMMIT -> PUSH -> PULL and then goes back to project

### There are 4 Methods to store our Notes on the remote storage (GitHub)

- From Hardest to the the Easiest:-
    1. The Git Command Line: It's a bit hard way. You will be able to use it once you finish Linux Class. This way is more beneficial to understand what happens behind the scenes. A & B are for storing locally and C is for storing on GitHub. To save notes, we use the mark down (.md) at the end of the name of the file.
        1. FOR FIRST TIME:
            1. cd Desktop (cd = change directory)
            2. mkdir gtst && cd gtst (mkdir = make directory)
            3. git init (init = initialize)
            4. git config —global user.name <Your Username> = When you make changes, git identifies you as the author by your username
            5. git config —global user.email <Your Email> = When you make changes, git identifies you as the author by your email
        2. FOR NORMAL WORKS:
            1. git status = Shows the status of your current project
            2. git add . = Telling git to add changes that you desire, the dot (.) will need some Linux 
               knowledge but it means Local Folder or the folder that contains your current project. In 	       other words, saves the changes as version 2.
            3. git commit -m <Your Comment> = This tells github to put whatever you said as a comment and 	       then commit to you repo.
            4. git log = list all the changes that happened in your repo.
        3. FOR GITHUB:
            1. git remove add origin <repository URL> = telling github to store all the changes to a 		       specific repo.
            2. git push -u origin master = pushing the wanted files.
            3. git clone <Your project link> = for downloading files into local storage.

### Software for note taking:
- **Obsidian**:- It saves your notes in the form of a .md, which will make it more easier to push to push notes to github. 
    - One of the many features of obsidian is that you can use a graph view to view all the notes on your app.
    - The other feature is that it can use a canvas page to draw to complex notes, workflow diagrams and many more.
    - You can also change your theme to whatever you want in the settings.
    - The main disadvantage of this software is you have to pay to sync your notes and vaults across different devices unlike notion, which have this feature for free.
- **VS Code**:- This software is mainly a coding software, but it can also be used for the purpose of taking notes on it with the .md file format.
    - The main advantage of using VS Code as your main note taking software is you can connect and sync your github account with your VS Code app and push your notes to your GitHub repo.
    - In order to push your notes into github, first you need to download git on your device and then you can contribute to your GitHub via VS Code.
- **Github website**:- For this method, you just need to login into GitHub's website and do what the simple basic steps.
    - Create repository on github
    - you can either upload existing files or create new files and then write your notes or whatever you want to write down on your github repo.
- **Github Desktop**:- GitHub Desktop is a free, open source application that helps you to work with code hosted on GitHub or other git hosting services.
    - Github Desktop on supported operating systems, which currently include macOS 10.13 or later and windows 10 64-bit or later.
    - Create a repository, Give it a name and a location and then finish creating the repo.
    - On this software, you can track changes that happened in your repo, and even publish it publically on github. but first you have to login into your github account.
    - From this software, you can open your notes on either VS Code or Obsidian. It's up to you.

### MARKDOWN:
- Markdown is the main file format for taking notes in github
- [Markdown](Markdown.md.png)
