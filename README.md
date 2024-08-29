# Remove Branches???
# delete remote :
    git push origin --delete dev
    git push origin --delete test
# delete local:
   git branch -d dev
   git branch -d test


   # Checkout branch without commit
   git stash git checkout dev or test

   # List tags
   git tag

# Delete tag
# del Remotely
    git push origin --delete <tagname>
# del locally
    git tag -d tagname
