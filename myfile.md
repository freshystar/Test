# Fix Github unverified commit
  ### Describe the bug
   I generated an ssh key-pair for my commits' signing and authenticatiion. I later added the desired key to my github account as an authentication key and another public key for signing. I would like to make it clear that when I added the ssh authentication key, any commit I pushed to my repository appeared as **verified**. But after adding a signing key, the commits pushed afterwards were marked **unverified**.The error message displayed was `No user is associated with the committer email.` 
