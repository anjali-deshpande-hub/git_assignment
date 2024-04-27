# Git Assignment - anjali-deshpande-hub

a. What is an issue?

'Issue' is a feature of Github. It allows users to track enhancements, bugs, tasks or any other issues that needs to be discussed by the team members. Team members can discuss ideas, suggest improvements or solutions, ask questions related to a project via 'Issues'. Issues can be assigned to a user/developer. There can be labels attached to an Issue. Labels are used to organize and categorize Issues. Milestones can be added to group issues and tracked. Issues have a status (e.g. Open/Close). Issues can be linked to pull requests. Issues provides a structured way to collaborate and manage developmemt cycle.  

b. What is a pull request?

Pull Request is a feature of GitHub that allows users to submit their work to a repository. The steps to add your work is to fork the repository, make changes like adding new features or fixing bugs, creating pull request, reviewing changes and merging changes. Pulling a request means that you are requesting the owners of the repository to pull changes from the users forked repository to the original repository and review it. The owner of the main repository can review the changes proposed in the pull request, suggest changes, add comments or approve changes. Pull request is a way for asking permission to add your code to the main project after it has been reviewed by another team member.   
It is a structured way for coders to propose their changes, ask for reviewing their changes and for the teams to collaborate share codebase for good code quality. It forces review to be a mandatory step in merging new code to the codebase.

c. How do I open up a pull request?

Opening a pull request is done through the browser by opening the repository on the GitHub website.
1. Fork the repository: First we fork the repository that we want to work with. It creates a copy of the repository under your GitHub account.
2. Clone the fork: Clone the forked repository on local machine using 
git clone <url of the forked repository>
3. Create a new branch: Create a new branch to make the changes and switch to the branch using:
git checkout -b <new_branch>
4. Make changes to the local repository
5. Stage and Commit changes using 
igit add <filename>
git comment <filename> -m "Commit comments"
6. Push changes to fork
git push -u origin <new_branch>
7. Navigate to the branch on the forked repository. Click on "Compare and pull request" button to open a new pull request.
8. Review the changes made and title and description and click "Create pull request".
9. The programmers that are tagged on the pull request will review the code and submit their comments. You can make further changes based, if required, and push changes again.
10. If changes are approved, the reviewer can merge the pull request into main repository.


d. Give me a step by step guide on how to add someone to your repository.

e. What is the difference between git and GitHub?

Git is a distributed version control system. It is used to track changes in the code. It allows multiple developers to work on the same code simultaneously and independently. It lets you keep track of any change you make while working on a project. In other words, it allows you to create different versions of your code (or project) without messing up the original code. Developers can create branches, work independently on those branches, merge changes and track changes.

GitHub on the other hand is a web-based platform that uses Git to host Git repositories. GitHub has additional features like Isues, Pull requests and other project management tools. It makes it easier for developers to share code and work on projects. GitHub is like a big community space where you can share your projects (open source) and contribute to other public projects

f. What does git diff do?
'git diff' is command used to get differences between two versions of the code. It is used to review changes before they can be committed. It is particularly useful when developers have to merge code and resolve conflicts. Sometimes, when iyou are about to merge the branches and there are conflicting changes between the branches you are merging, 'git diff' helps in understanding what the conflicts are.

'git diff' without any parameters or options shows the difference between the currengt working directory and the last commit.

g. What is the main branch?

The 'main branch' is the primary branch from where the development starts. Its usually a stable, tested and releasable version of the project. Its the branch from whieh other new branches are created for making bug fixes or for adding new features.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

No. Pushing your changes directly to the main branch is usually not recommended. It is especially not recommended for projects that are deployed to a production environment. Its a good practice to branch from main branch to work on specific feature request or for fixing bugs. That way, you are not affecting the main code or the main branch. It also provides an opportunity for your peers to review the branched code, make the necessary  
