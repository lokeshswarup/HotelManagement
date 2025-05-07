## Contributing Guidelines

Thank you for considering contributing to the repository. This guide details all the general information that one should know before contributing to the project.
Please stick as close as possible to the guidelines. That way we ensure that you have a smooth experience contributing to this project.

### General Rules :
These are in general rules that you should be following while contributing to an Open Source project :

- Be Nice, Be Respectful (BNBR)
- Check if the Issue you created, exists or not.
- While creating a new issue make sure you describe the issue clearly.
- Make proper commit messages and document your PR well.
- Always add Comments in your Code and explain it at points, if possible add Doctest.
- Always create a Pull Request from a Branch; Never from the Main.
- Follow proper code conventions because writing clean code is important.

<h1>Instructions to Contribute</h1>
The Open source Community is awesome, to be a part of it you can start contributing and help people with their projects, here's a guide to do exactly that!
before you start here is something you should know:
<br>
1. <a href = "https://hacktoberfest.com/participation/">Hacktoberfest guide</a> <br>
2. <a href = "https://opensource.guide/code-of-conduct/">Code of Conduct</a>

<h3> How to Contribute </h3>
<p>
 Step 1: Fork this repository. <br>
 Step 2: Go to your GitHub profile and you will find a repository with the same name as the project. Clone this repository either using the "Download zip" button under the code section or using git commands,
         you can use the command:

    git clone `link of the project (your fork)`

  to clone your forked repository into your local machine.

  now change your dirctory to the project using the command:

    cd NAME_OF_REPOSITORY

 Now check if your fork is set to remote origin. A remote is basically a URL that points to the project repository and the one you forked. The project repository is called the 'Upstream' remote and your fork is called the 'origin' remote. You can check the status of remotes using the command: 

    git remote -v 

  you should see the word origin next to your fork, if you don't see it, you can use the command to add it: 

    git remote add origin URL_OF_FORK

  now add the project repository as 'Upstream' remote using the command:

    git remote add upstream URL_OF_PROJECT

  now again use the command:

    git remote -v

  to check the status of remotes.


  Now to update your repository with the main project, you need to use the command:

    git pull upstream master

  or

    git pull upstream main

  depending upon the branch of the main project.

  Now, you should create a new branch as working in the main branch could be risky incase of an error or bugs, to add a new branch you can use the command:

    git checkout -b BRANCH_NAME

  This also switches you to the new branch.

  And now you can make whatever changes you feel like to the code using various tools.
  After you are done making the required changes, you can stage those changes using the command: 

    git add -A

  and commit them using:

    git commit -m "A good description to the changes you made to the code."

  To push these changes you can use the command:

    git push origin BRANCH_NAME

  Going back to GitHub you may see a highlighted area which says "Compare and Pull Request", click that.
  This will send a pull request.
