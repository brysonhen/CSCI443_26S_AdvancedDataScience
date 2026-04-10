every time the professor pushes new lectures your workflow will be:

      git pull origin main
      
      GIT_LFS_SKIP_SMUDGE=1 git pull upstream main
      
      git add .
      
      git commit -m "sync upstream"
      
      git filter-branch --force --index-filter \
      
      'git rm --cached --ignore-unmatch *.pdf *.mp4' \
      
      --prune-empty --tag-name-filter cat -- --all
      
      git push origin main --force
      
After running those commands, just pull in Databricks like normal — click the branch button → Pull.


That's it. Then when you finish homework, commit and push from Databricks as usual, and when you need to submit, download the .ipynb from your GitHub and upload to Blackboard.
