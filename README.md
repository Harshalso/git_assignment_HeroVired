
Q.1

// Repository Created:
Logged in to your GitHub account.
Click on "New" to create a new repository.

Set the repository name to git_assignment_HeroVired.
Choose Private visibility.
Optionally, initialize with a README.

Clone the Repository in Local PC
Create and Switch to the 'dev' Branch:
Create a file named calculator.py

Add the codes given
Commit and Push to dev Branch

Merge this branch with the main branch and make a release of version 1
Add the codes given 
Commit and Push to dev Branch

Merge this branch with the main branch and make a release of version 1

Create Version 1 Release on GitHub:

Go to your repository on GitHub.
Click on "Releases" > "Draft a new release".
Tag version: v1.0.
Release title: Version 1.0.
Description: Summarize the features.
Click "Publish release".

Invite collaborators
Setting > Manage Access > Invite a collaboraton
Setting > Manage Access > Invite a collaborator 

Implement a feature by creating a new branch called feature/sqrt

Modify calculator.py by implementing sqrt function

commit and push the changes

fix bug in the divide function on the dev branch and keep your feature/sqrt branch up-to-date

Update the divide function..

Update the divide function.. 


updation of feature/sqrt branch

Merge dev into feature/sqrt

Resolve any merge conflicts

pushed updated version

Created a pull request targeting the main branch

Requested review of code from teammates

Merge the feature/sqrt branch into the dev branch after approval

Test in the dev branch, merge into the main branch, and create a version 2 release


Both of the branch dev branch and main contain v1, v2 but main branch as act as staitic versions and dev branch changed

Both of the branch dev branch and main contain v1, v2 but main branch as act as staitic versions and dev branch changed 


Q.3)


- Begin by creating a new branch called `feature/circle-area` to work on the circle area feature.
- After partially implementing the feature, use `git stash` to save the changes and ensure the working directory is clean.
- Next, create another branch, `feature/rectangle-area`, for the rectangle area feature.
- Similarly, work on the rectangle area feature and stash those changes as well.
- Switch back to the `feature/circle-area` branch, retrieve the stashed changes, complete the implementation, and commit the changes.
- Push the `circle-area` feature to the remote repository.
- Then, switch back to the `feature/rectangle-area` branch, retrieve the stashed changes, complete the implementation, and commit the changes.
- Push the `rectangle-area` feature to the remote repository.
- Finally, create pull requests for both features, have them reviewed, and merge the branches into the `dev` branch.


Q.2

Summary of the steps taken:
To handle large binary files efficiently in the "git_assignment_HeroVired" repository, 
start by creating a branch named `lfs`. Initialize Git LFS with `git lfs install` and 
configure it to track large binary files, such as `.mp4` files, using `git lfs track "*.mp4"`. 
Add a large file (e.g., a video file over 200MB) to the repository and commit it. 
Push the changes to the remote repository, where Git LFS will manage the large file efficiently. 
Finally, clone the repository on another machine to ensure that the large file is downloaded correctly and managed by Git LFS.

