# Git DEMO 
Learning Freecodecamp.org!

**->git clone <ssh>**
  
  Generating ssh key url : https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
  ssh-keygen -t ed25519 -C "your_email@example.com"
  
  ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
  add passphrase
  
  Starting SSH agent
  eval $(ssh-agent -save)
  gives agent id
  
  add identity
  ssh-add ~/.ssh/id_rsd
  
  Copying key from id_rsa.pub file
  clip < ~/.ssh/id_rsa.pub
  
  Go to git profile add new SSH key
                          
  git clone <ssh>

   
  .git hidden folder of git repository -> ls -la command to list all files
  .git holds all the changes and commits of the repository
  
  ## Steps to commit and push the changes to git hub
  
  ->Edit the file
  ->git status : This command shows all the changes made to repository but not saved ie; updated files, deleted files, created files.
  image.png
  ->git add . : To add all the tracked and untracked changes to stage area
  image.png
  ->git push origin <branch name>: to update changes to remote repository where our git hub is hosted

## Steps to initalize git repo from local repository
  
  
  
  
  
  
