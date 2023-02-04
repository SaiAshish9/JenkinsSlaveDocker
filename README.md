```
brew install jenkins-lts
cd /usr/local/Cellar/jenkins-lts/2.375.2
edit port at homebrew.mxcl.jenkins-lts.plist 

brew services list
Name              Status User File
jenkins-lts       none   root 
kafka             none        
mongodb-community none        
redis             none        
zookeeper         none

brew services start jenkins-lts
==> Successfully started `jenkins-lts` (label: homebrew.mxcl.jenkins-lts)

brew services restart jenkins-lts
brew services stop jenkins-lts
```

<img width="839" alt="Screenshot 2023-02-04 at 11 40 09 PM" src="https://user-images.githubusercontent.com/43849911/216782848-1364e583-1b9d-4179-90f3-043180174fc0.png">
