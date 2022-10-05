## What is GitHub?
> GitHub is an "open source control system". It allows the users to keep track of changes made to their code using **branches**,
> where users can "safely experiment" ideas in a safe coding area. If any bugs appear, the users can revert to a 
> previous version using these **branches**.
> When the user is done making changes to a file, they can "**commit**" these changes allowing them to save and keep track of their progress.
> After the changes are committed, the users can choose to "**push**" these changes to GitHub - which essentially transfers 
> the changes previously committed, from a local repository to a remote repository.
> Users also have access to other public repositories by "**cloning**" them. Using the clone command allows users to make a copy
> of the repository into another location. 
> "**Fetch**" is anothe Git command that allows users to download contents from a remote repository. The command is also used with
> git remote, git branch, and git checkout. 
> "**Pull**" requests allows users to let other collaborators know that changes were made to a branch. The changes can be discussed 
> and reviewed before committing the final changes. 
> Users can use the "**merge**" command to take two independent line of development in two branches and "merge" them into one branch.
> Essentially combining multiple versions of a file or folder. 

>> ## Installing Git 
>> - Download from: https://git-scm.com/downloads
>> - Create a Github account: https://github.com/join
>> ## What is Git?
>> Git is a *free*, open source version control system used for tracking the changes made in files. This works with GitHub
>> as GitHub is a cloud-based hosting service allowing users to better manage their repositories. 

## What is Webstorm?
 > Webstorm is an IDE that also for coding in JS, TypeScript, React, Node.js, HTML, and style sheets.
 >> ### How to setup Webstorm w/ Git and GitHub
 >> - After you download Webstorm you can connect your existing (*or newly created*) GitHub account
 >>   - If you did not download Webstorm -> download from: https://www.jetbrains.com/student/
 >>     - Enter your student information to get the **FREE** student version of Webstorm
 >> - Ctrl + Alt + S to open the system preferences menu
 >> - Select Version control Git and enter the path to Git.exe (*if not installed, downlaod here:* https://git-scm.com/downloads)
 >> - Ctrl + Alt + S to open the system preferences menu
 >> - Select Appearance and Behavior -> System Settings -> Passwords 
 >>   - Here you add in your password for GitHub
 >> - Now your GitHub is connected to your Webstorm and you can now create repos through Webstorm as well as commit and push through Webstorm.

## How to create Repositories Through GitHub and Webstorm
> ### Creating Repositories Through GitHub
>> - In the upper-right corner of your screen (*next to your pfp*), click the plus button.
>> - Click "Create New Repository"
>>   - In the repository setup, you can add a README.md file (*like this one*) and you can set the repository to either public (*anyone can see it*) or private (*you can choose who can and cannot see it*).

> ### Creating Repositories Through Webstorm
>> - Select VCS -> Import -> Version Control
>> - Choose where the repository will be created
>> - Give it a name and create

> ### Importing a Repository from GitHub
>> - From Main page Select Version Control-> Git **OR** From within Webstorm Select VCS -> Version Control -> Git
>> - Enter Github repository name 
>> - Enter local path name

> ## Glossary
>> - Branch: Allows users to fix bugs and safely experiment their ideas in a "contained area of your repository"
>> - Clone: A command that is used to make a copy or "clone" an already existing repository in a different location.
>> - Commit: Used to track the progress and changes of the user's code. Users should **ALWAYS** include a message with 
>>           their commit explaining what the commit was
>> - Fetch: A command used to download the contents of a remote repository. Works with other commands 
>>          to update a local repository to match the state of a remote repository.
>> - Git: A version control allowing the user to manage and track their source code's history. 
>> - GitHub: A cloud-based hosting service that makes it easier for users to track their Git repositories.
>> - Merge: A command used to combine two lines of development created by a Git branch and "merging" them into one branch.
>> - Merge Conflict: Occurs when two collaborators try to edit the same code. To resolve a conflict, the two developers 
>>                   must work in different branches.
>> - Push: A command used to update a remote repository with a local repository's content.
>> - Pull: A request that lets other collaborators know about the user's changes that they pushed. Within the request,
>>         collaborators can discuss and review the changes before finally committing the pull request. 
>> - Remote: A remote repository that is hosted on the internet or another network.
>> - Repository: Tracks and saves the changes made to a file in a Git project.
