# Git and GitHub Introduction
## Git
Suppose we created a file. To store it permanently we use save command. `Save` command stores our file to any secondary storage device. Suppose we made some changes to the file. Now this modified file can be called as new version of the existing file. If we close the file `without saving` then we still have the older version of file. But we can't access the new version (means the file with the changes) any more, because without saving we have closed it. If we want to keep both the versions of file in our system then we have to use `save as` command to save the new version with a new name. Here you have to be intelligent enough to write the name in such a way that by seeing the name you can identify the changes you made in that version.

Instead of all these headaches, we can use Git to control our versions. In software development we have to keep track of versions. Suppose any error occoured in any version then we should have a way to revert back to older version. We have to memeber one thing here, when we are working on a new version, we change so many files and at different portions of that file. So manually keeping track of all these options are nearly impossible.

So we can say, Git is a version control system that lets us manage and keep track of our software development history.

A Git Repository can be defined as a virtual file storage system which tracks and saves the hostory of all changes made to the files in a git project.

## GitHub
GitHub is a web-based Git repository hosting service. It offers all of the distributed version control and source code management. 

In real world, If you have created any project then definitely you would want to show it to others on your bio-data as well as you will like to show them your live website. These all can be done through GitHub.

## What we will do ?
We will create repository for our project-1 on GitHub and make it live so that we can share it to others. In this lesson we will not discuss all the commands of Git and GitHub. We will discuss only the required commands. Rest of the commands we will discuss later when we need to implement those.

### Steps
- [Read this and create an account on GitHub](https://www.toolsqa.com/git/how-to-create-github-account/)
- [Read this and Create A Repo in GitHub](https://docs.github.com/en/get-started/quickstart/create-a-repo). Remember to read upto point number 6. The name of your repository should be `Project1-With-Subrat-Sir`.
- [Read this documentation to install Git on Windows](https://phoenixnap.com/kb/how-to-install-git-windows)
- [Read this and clone the repository](https://www.toolsqa.com/git/how-to-create-github-account/) to the created folder in `D` drive during project creation.
- It will create a new folder `Project1-With-Subrat-Sir`. Copy your project files to this folder.
- Open command prompt. Move to that folder using `CD` command if you are using windows command prompt.
- Type `git branch` and press enter. It will show you that you are in main branch.
- Type `git status` : The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.
- Type `git add .` : The git add command adds a file to the Git staging area.
- Type `git commit -m "Add : project files"` : Takes the staged snapshot and commits it to the project history.
- Type `git push` : The git push command is used to upload local repository content to a remote repository on GitHub.

Now our project is on a web server. So we can call it now a website and any one with the website link can see that.

- The last step is to make it live so any one with the link can see the result.
  - [Read point 6,7,8 and 9 of this topic to make your website live](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site). On point no-8 you can choose `public` option so that others can see your source code also.


Congratulations! your website is live now. It's URL will look something like this : `https://<github_user_name>.github.io/<repository_name>/` 



<p align="center" width="100%">
    <a href="#">
        <img width="33%" src="https://github.com/subratsir/HTML-CSS-JavaScript-Basics/blob/main/img/next-lesson1.png" width="250px" height="auto" /> 
    </a>
</p>

<p align="center" width="100%">
<h1>Have a question ?</h1>
<p>Chat with our friendly community in our Discord Chatrooms!</p>
<a href="https://discord.gg/KYYWfcVU"><img src="https://quoramarketing.com/wp-content/uploads/2021/08/Fix-Discord-Error-Code-96.jpg" alt="Open Discord" width="150px" height="auto" /></a>
</p>

## Hey <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">, Follow [Subrat Sir!](https://github.com/subratsir) 

<a href="https://in.linkedin.com/in/subratsir">
  <img align="left" width="24px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg"  />
</a>
<a href="https://twitter.com/SubratSirIndia">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="mailto:subrat.ku.dash@gmail.com">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />
</a>
<a href="https://www.youtube.com/channel/UCTCmj3TOBxI_5f1J-n7kN5A">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />
</a>
<a href="https://discord.gg/KYYWfcVU">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/discord.svg" />
</a>

<br />
