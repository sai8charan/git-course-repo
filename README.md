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
  
  
  
