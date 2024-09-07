

Q.2

Summary of the steps taken:
To handle large binary files efficiently in the "git_assignment_HeroVired" repository, 
start by creating a branch named `lfs`. Initialize Git LFS with `git lfs install` and 
configure it to track large binary files, such as `.mp4` files, using `git lfs track "*.mp4"`. 
Add a large file (e.g., a video file over 200MB) to the repository and commit it. 
Push the changes to the remote repository, where Git LFS will manage the large file efficiently. 
Finally, clone the repository on another machine to ensure that the large file is downloaded correctly and managed by Git LFS.
