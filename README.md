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

cat /Users/saiashish/.jenkins/secrets/initialAdminPassword
f8762197372b44d89991f973247aa3df

brew services restart jenkins-lts
brew services stop jenkins-lts
```

<img width="839" alt="Screenshot 2023-02-04 at 11 40 09 PM" src="https://user-images.githubusercontent.com/43849911/216782848-1364e583-1b9d-4179-90f3-043180174fc0.png">

<img width="1791" alt="Screenshot 2023-02-04 at 11 50 16 PM" src="https://user-images.githubusercontent.com/43849911/216783216-7b736f9e-b9c1-403a-baa0-4e917c03eaf0.png">


<img width="1497" alt="Screenshot 2023-02-04 at 11 51 12 PM" src="https://user-images.githubusercontent.com/43849911/216783240-a3406edc-cabf-4b46-98ad-0d2f603fc2e9.png">

<img width="1763" alt="Screenshot 2023-02-04 at 11 56 13 PM" src="https://user-images.githubusercontent.com/43849911/216783474-d2dc0935-8f18-4413-8db2-402edecc4d48.png">

<img width="1777" alt="Screenshot 2023-02-04 at 11 56 44 PM" src="https://user-images.githubusercontent.com/43849911/216783499-bd266c64-1902-4abd-9c09-7e275ebb89dc.png">

<img width="1789" alt="Screenshot 2023-02-04 at 11 57 25 PM" src="https://user-images.githubusercontent.com/43849911/216783533-0797d446-9172-4510-bb53-44ca2f4d9c2d.png">

```
Set up Linux Machine As Jenkins Slave.

Manage Nodes => New Node

```

<img width="1789" alt="Screenshot 2023-02-05 at 12 02 47 AM" src="https://user-images.githubusercontent.com/43849911/216783781-0117fc7b-9da2-44f4-a58e-bd8d2c13641a.png">

<img width="1789" alt="Screenshot 2023-02-05 at 12 03 23 AM" src="https://user-images.githubusercontent.com/43849911/216783805-4535be34-9b05-41c2-b4a0-f4d15f86bc42.png">

<img width="1788" alt="Screenshot 2023-02-05 at 12 03 58 AM" src="https://user-images.githubusercontent.com/43849911/216783836-6e6c8e76-7a93-40cd-87a9-596fed312c99.png">

<img width="1291" alt="Screenshot 2023-02-05 at 12 05 17 AM" src="https://user-images.githubusercontent.com/43849911/216783882-9e27204f-4ea9-4c0e-ac8f-a4bb55fa0da3.png">





