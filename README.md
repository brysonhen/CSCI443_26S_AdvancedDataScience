every time the professor pushes new lectures your workflow will be:
      git pull origin main
      GIT_LFS_SKIP_SMUDGE=1 git pull upstream main
      git add .
      git commit -m "sync upstream"
      git filter-branch --force --index-filter \
      'git rm --cached --ignore-unmatch *.pdf *.mp4' \
      --prune-empty --tag-name-filter cat -- --all
      git push origin main --force
