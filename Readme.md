
## Hello Everyone, Welcome to Git Guide!
- Yo, Piyush here!

## Branching & Merging ##
-> Branching in git allow you to create different versions of your project
-> For creating new Branch-
## git branch branch_name
-> And go to this branch-
## git checkout branch_name
-> If you do these two-step - creating branch or switching to that in one go then -
## git checkout -b branch_name
-> For creating a new branch with someone existing branch-
## git branch new_branch_name source_branch

- "I'm adding from test-branch"

-> An upstream branch is a remote branch that your local branch tracks.
-> when you set an upstream branch using set upstream you are essentially linking your local branch to a branch on a remote repo through this command you push a local feature branch to the origin remote repository and then you set the upstream branch for your local feature branch to track origin feature branch.

-> Alternatively you also use this command -
- ## git push -u origin branch_name


        ## Typical Workflow ##
          1. Clone the repository
          2. Create a new branch from the main or another branch
          3. Make your changes 
          4. Push the branch to the remote repo
          5. Open a Pull Request
          6. Merge the changes
          7. Pull the merged changes into your local main branch 
          8. Repeat from step 2


 ## Git Saviour Commands ##
  -> git reset --soft <commit-hash>
  -> git rest <commit-hash>
  -> git reset --hard <commit-hash>