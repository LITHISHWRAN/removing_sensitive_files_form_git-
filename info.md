## removing_sensitive_files_form_git-


**Problem:** To remove sensitive files from git if accidently pushed.



- *pip install git-filter-repo*
- *git clone "repo-link"*
- *cd repopath*
- *git 
- *git filter-repo --path .env --invert-paths*
- *git push origin --force --all*
- *git push origin --force --tags*

