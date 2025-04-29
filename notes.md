error: failed to push some refs to 'https://github.com/devmaina/libs-safari-africa.git'
USER:liberty tours and travels$ git remote add upstream https://github.com/devmaina/libs-safari-africa.git && git push --force upstream HEAD:main
error: remote upstream already exists.
USER:liberty tours and travels$ git remote set-url upstream https://github.com/devmaina/libs-safari-africa.git && git push --force upstream HEAD:main
remote: Permission to devmaina/libs-safari-africa.git denied to ibconcept.
fatal: unable to access 'https://github.com/devmaina/libs-safari-africa.git/': The requested URL returned error: 403
USER:liberty tours and travels$ 
USER:liberty tours and travels$ 

 branch master
Your branch is up to date with 'upstream/master'.

nothing to commit, working tree clean
USER:liberty tours and travels$ git push upstream --delete main && git push --set-upstream upstream master
To https://github.com/devmaina/libs-safari-africa.git
 ! [remote rejected] main (refusing to delete the current branch: refs/heads/main)
error: failed to push some refs to 'https://github.com/devmaina/libs-safari-africa.git'       
USER:liberty tours and travels$ 
USER:liberty tours and travels$ 