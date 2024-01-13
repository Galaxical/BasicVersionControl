# BasicVersionControl
Explain about basic version control with respect to git and github in a README.md file.

I. What is version control system?
While working on a software development project which involves multiple collaborators, it is important that a detailed means of monitoring and tracking changes made in the codeblocks for better effects should be implemented. 

The term version control explains a process of keeping record, blueprint of a change made in a code block, thereby ensuring an easy optimization of codeblockes without actually affecting the main source. Think of it as a tree, with trunk (master branch or main) and branches (actual file/s edited). 

The main (master branch) holds the testable codes, devoid of bugs which are ready to run any time. While further developments will go on, there will be the constant need pulling the main source code to other branches, to exclusively work on the brached code without tempering with the main source code. 

This procedure enables developers to add, commit, pull, push, clone, merge, comment and submit merge requests; as will be needed by a developer to control various editing versions contributed by other collaborators in their several branches. 

Throughout the periods of building and optimizing products, version control systems allows the documentation of the products development evolution; for downgrade or further upgrades, such that the developers can go back in time to revisit their codes, testing multiple branches of code edits with the main (master branch) to ensure which gives the required result. 




II. Difference between git and github
Think of Git as a notebook where you track your code revisions, and GitHub as a cloud locker where you store and share those notebooks with others.

It is essential for any developer to know the difference between Git and GitHub. Git's version control capabilities are fundamental for managing your code effectively, while GitHub provides a platform to collaborate with others and showcase your work.

Here's the basic knowledge that differentiates git from gitHub
Function: Git is the engine for tracking changes, while GitHub is the platform for storing and sharing those changes.

Location: Git works primarily on your local machine, while GitHub stores your code in the cloud.

Access: Git is command-line driven, while GitHub offers a web interface.

Community: Git is primarily for individual use, while GitHub has a strong social coding community aspect.

In simpler terms, think of Git as a notebook where you track your code revisions, and GitHub as a cloud locker where you store and share those notebooks with others.

Git's version control capabilities are fundamental for managing your code effectively, while GitHub provides a platform to collaborate with others and showcase developer’s works. 


III. Other alternatives to github
1.	Microsoft Azure DevOps server
2.	GitLab
3.	BitBucket



IV. Git fetch is the process of asking for an update from a co-author’s code branch; you can what is written there but your own code remains untouched. It is like checking out a code in a branch without merging it with your own code work yet.

Git pull is like actually accepting your co-author's changes in the code branch, and merging them into your own code. This is usually done when you're ready to incorporate their work into your own blocks of codes. 

V. What is git rebase?
This is the procedure whereby code updates made in different branches are fetched and pulled together with the main (masterBranch) (without any additional joins or gaps). This process replays the commits one after the other with the new rebase codes created with a cleaner history; it rewrites the branch (main or masterBranch) history while creating a linear history that is easy to read and understand. 
•	“git rebase main feature”

VI. What is git cherry-pick?
This involves adding a desired commit from a numerous code branch to a desired branch location. Unlike merging or rebasing, cherry-picking allows the developer to choose a specific commit without pulling the entire branch 
•	“git cherry-pick”
