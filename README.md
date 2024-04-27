# Git Assignment - anjali-deshpande-hub

<i><b>a. What is an issue?</b></i>

'Issue' is a feature of Github. It allows users to track enhancements, bugs, tasks or any other issues that needs to be discussed by the team members. Team members can discuss ideas, suggest improvements or solutions, ask questions related to a project via 'Issues'. Issues provides a structured way to collaborate and manage developmemt cycle. 

Issues can be assigned to a user/developer. There can be labels attached to an issue. Labels are used to organize and categorize Issues. Milestones can be added to group issues and tracked. Issues have a status e.g. Open/Close. Issues can be linked to pull requests. 

<i><b>b. What is a pull request?</b></i>

'Pull Request' is a feature of GitHub that allows users to submit their work to a repository. The steps to add your work is to fork the repository, make changes like adding new features or fixing bugs, creating pull request, reviewing changes and merging changes. 

Pull request is a way for asking permission to add your code to the main project after it has been reviewed. The owner of the main repository can review the changes proposed in the pull request, suggest changes, add comments or approve changes.

It is a structured way for coders to propose their changes, ask for reviewing their changes and for the teams to collaborate the changes to the codebase. This ensures a better quality of code. It forces review to be a mandatory step in merging new code to the codebase.

<i><b>c. How do I open up a pull request?</b></i>

Opening a pull request is done through the browser by opening the repository on the GitHub website.
1. Fork the repository: First we fork the repository that we want to work with. It creates a copy of the repository under your GitHub account.
2. Clone the fork: Clone the forked repository on local machine using:

git clone \<url of the forked repository\>
3. Create a new branch: Create a new branch to make the changes and switch to the branch using

git checkout -b \<new_branch\>
4. Make changes to the local repository
5. Stage and Commit changes using

git add \<filename\>

git comment \<filename\> -m "Commit comments"
6. Push changes to fork

git push -u origin \<new_branch\>
7. Navigate to the branch on the forked repository. Click on "Compare and pull request" button to open a new pull request.
8. Review the changes made and add title and description and click "Create pull request".
9. The programmers that are tagged on the pull request will review the code and submit their comments. You can make further changes based on the review and push changes again.
10. If changes are approved, the reviewer can merge the pull request into main repository.


<i><b>d. Give me a step by step guide on how to add someone to your repository.</b></i>

To add someone to a repository on GitHub, you need to invite them as a collaborator. 
1. Go to GitHub repository that you want to add someone to. Click on the "Setting" tab at the end.

See snapshot below:

![Alt text](https://github.com/anjali-deshpande-hub/git_assignment/blob/assignment/image1.jpg "Collaborator")

2. In the left sidebar, under 'Access', there is a 'Collaborators' link. Click on it.

3. It opens up a page that has 'Manage Access" with "Add people" button the the right. 

See snapshot below:
![Alt text](https://github.com/anjali-deshpande-hub/git_assignment/blob/assignment/image2.jpg "Manage Access")

Search for the username you want to add as a collaborator. Click "Add \<username\> to this repository\>

See snapshot below:

![Alt text](https://github.com/anjali-deshpande-hub/git_assignment/blob/assignment/image3.jpg "Manage Access")

4. GitHub sends an email invitation to the user you have added as a collaborator. They will have to accept the invitation to become a collaborator
After the user does that, you can assign thema roles based on permissions granted. They can have admin, write or read access to the repository.

See snapshot below:

![Alt text](https://github.com/anjali-deshpande-hub/git_assignment/blob/assignment/image3.jpg "Manage Access")

<i><b>e. What is the difference between git and GitHub?</b></i>

Git is a distributed version control system. It is used to track changes in the code. It allows multiple developers to work on the same code simultaneously and independently. It lets you keep track any change you make while working on a project. In other words, it allows you to create different versions of your code (or project) without messing up the original code. Developers can create branches, work independently on those branches, merge changes and track changes.

GitHub on the other hand is a web-based platform that uses Git to host Git repositories. GitHub has additional features like Isues, Pull requests and other project management tools. It makes it easier for developers to share code and work on projects. GitHub is like a big community space where you can share your projects (open source) and contribute to other public projects

<i><b>f. What does git diff do?</b></i>

'git diff' is a command used to get differences between two versions of the code. It is used to review changes before they can be committed. It is particularly useful when developers have to merge code and resolve conflicts. Sometimes, when you are about to merge the branches and there are conflicting changes between the branches you are merging, 'git diff' helps in understanding what the conflicts are.

'git diff' without any parameters or options shows the difference between the current working directory and the last commit.

<i><b>g. What is the main branch?</b></i>

The 'main branch' is the primary branch from where the development starts. It's usually a stable, tested and releasable version of the project. Its the branch from which other new branches are created for making bug fixes or for adding new features.

<i><b>h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?</b></i>

No. Pushing your changes directly to the main branch is usually not recommended. It is especially not recommended for projects that are deployed to a production environment. Its a good practice to branch from main branch to work on adding specific feature request or for fixing bugs. That way, you are not affecting the main code or the main branch. It also provides an opportunity for your peers to review the branched code so that you can improve the quality of code that is incorporated or merged to the main branch.  
