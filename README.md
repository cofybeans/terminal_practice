### Summary of Method 1 (Terminal) with chatgpt assistance

1. **Created a Local Repository**:
   - Initialized a new Git repository locally.

2. **Created and Edited `.gitignore`**:
   - Added necessary patterns to the `.gitignore` file to exclude certain files from being tracked.

3. **Committed the `.gitignore` File**:
   - Staged and committed the `.gitignore` file to the local repository.

4. **Created a Remote Repository on GitHub**:
   - Created a new repository on GitHub named `terminal_practice`.

5. **Linked Local Repository to Remote Repository**:
   - Added the remote repository URL to the local Git configuration.

6. **Generated a Personal Access Token**:
   - Created a PAT on GitHub for authentication.

7. **Pushed Local Changes to Remote Repository Using PAT**:
   - Successfully pushed the local `master` branch to the remote repository using the PAT for authentication.

### Verification

You can verify that everything is set up correctly by checking your repository on GitHub:

1. **Visit Your GitHub Repository**:
   - Open your web browser and go to your GitHub repository URL: `https://github.com/cofybeans/terminal_practice`

2. **Check the Repository Contents**:
   - Verify that the `.gitignore` file and any other committed files are present.

3. **Check Branch Tracking**:
   - Ensure that the local `master` branch is tracking the remote `master` branch:
     ```sh
     git branch -vv
     ```
P.S: Summary of Scopes and Permissions (Personal access token):
1. repo
2. workflow
3. gist
4. read (download and install packages)

Any further advise from Seniors (you guys), that would be great help in my python jounery and fully appricate!
Cofybeans
