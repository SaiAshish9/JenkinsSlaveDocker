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
<img width="1559" alt="Screenshot 2023-02-07 at 1 28 32 AM" src="https://user-images.githubusercontent.com/43849911/217072316-35ef371f-3e03-4ec4-8f28-23d699d24b3e.png">

<img width="839" alt="Screenshot 2023-02-04 at 11 40 09 PM" src="https://user-images.githubusercontent.com/43849911/216782848-1364e583-1b9d-4179-90f3-043180174fc0.png">

<img width="1791" alt="Screenshot 2023-02-04 at 11 50 16 PM" src="https://user-images.githubusercontent.com/43849911/216783216-7b736f9e-b9c1-403a-baa0-4e917c03eaf0.png">

<img width="1497" alt="Screenshot 2023-02-04 at 11 51 12 PM" src="https://user-images.githubusercontent.com/43849911/216783240-a3406edc-cabf-4b46-98ad-0d2f603fc2e9.png">

<img width="1763" alt="Screenshot 2023-02-04 at 11 56 13 PM" src="https://user-images.githubusercontent.com/43849911/216783474-d2dc0935-8f18-4413-8db2-402edecc4d48.png">

<img width="1777" alt="Screenshot 2023-02-04 at 11 56 44 PM" src="https://user-images.githubusercontent.com/43849911/216783499-bd266c64-1902-4abd-9c09-7e275ebb89dc.png">

<img width="1789" alt="Screenshot 2023-02-04 at 11 57 25 PM" src="https://user-images.githubusercontent.com/43849911/216783533-0797d446-9172-4510-bb53-44ca2f4d9c2d.png">

```
Set up Linux Machine As Jenkins Slave.

Manage Nodes => New Node

Launch agent
```

<img width="1789" alt="Screenshot 2023-02-05 at 12 02 47 AM" src="https://user-images.githubusercontent.com/43849911/216783781-0117fc7b-9da2-44f4-a58e-bd8d2c13641a.png">

<img width="1789" alt="Screenshot 2023-02-05 at 12 03 23 AM" src="https://user-images.githubusercontent.com/43849911/216783805-4535be34-9b05-41c2-b4a0-f4d15f86bc42.png">

<img width="1788" alt="Screenshot 2023-02-05 at 12 03 58 AM" src="https://user-images.githubusercontent.com/43849911/216783836-6e6c8e76-7a93-40cd-87a9-596fed312c99.png">

<img width="1291" alt="Screenshot 2023-02-05 at 12 05 17 AM" src="https://user-images.githubusercontent.com/43849911/216783882-9e27204f-4ea9-4c0e-ac8f-a4bb55fa0da3.png">

<img width="1324" alt="Screenshot 2023-02-05 at 12 16 33 AM" src="https://user-images.githubusercontent.com/43849911/216784330-795c74a4-541a-4e47-8970-a65d5063a1d7.png">

<img width="646" alt="Screenshot 2023-02-06 at 1 05 27 AM" src="https://user-images.githubusercontent.com/43849911/216840785-20365f1a-4b93-4424-9b7c-7e9e1026b8d3.png">

<img width="1272" alt="Screenshot 2023-02-06 at 1 08 47 AM" src="https://user-images.githubusercontent.com/43849911/216840919-185e9c26-8fce-4ed8-9e5e-ee043f0fae2b.png">

<img width="1070" alt="Screenshot 2023-02-06 at 1 26 50 AM" src="https://user-images.githubusercontent.com/43849911/216841745-021d86eb-ab06-4477-b75c-6e337ebc7a76.png">

```
JNLP (Java Network Launch Protocol) allows us to install some of the remote applications inside client machine. We need to copy JAVA jar files of node inside jenkins agent.

When we run that agent.jar , automatically it will connect to controller
```

<img width="1275" alt="Screenshot 2023-02-06 at 1 46 43 AM" src="https://user-images.githubusercontent.com/43849911/216842654-ac42eb3f-730f-4f90-be10-7b5d12b87daa.png">

<img width="403" alt="Screenshot 2023-02-06 at 1 50 18 AM" src="https://user-images.githubusercontent.com/43849911/216842778-a64f58ba-6684-42ca-b8d5-b5d5b69a8147.png">

<img width="1141" alt="Screenshot 2023-02-06 at 11 59 54 PM" src="https://user-images.githubusercontent.com/43849911/217055283-c54443cd-f1c0-4274-b819-de220daa3045.png">

<img width="658" alt="Screenshot 2023-02-07 at 12 07 58 AM" src="https://user-images.githubusercontent.com/43849911/217056865-4b4263c1-9d9c-4e7d-8903-644b34993176.png">

<img width="662" alt="Screenshot 2023-02-07 at 12 08 19 AM" src="https://user-images.githubusercontent.com/43849911/217056906-c5f677c6-b444-4a96-ae4b-163c83ed1a7a.png">

chmod 700 ~/.ssh

<img width="1561" alt="Screenshot 2023-02-07 at 12 42 31 AM" src="https://user-images.githubusercontent.com/43849911/217063379-88628dda-2c01-4cf8-876e-eff069051160.png">

<img width="1564" alt="Screenshot 2023-02-07 at 12 52 24 AM" src="https://user-images.githubusercontent.com/43849911/217065320-64557397-bc26-4503-a3b4-d74924f04d64.png">

<img width="1564" alt="Screenshot 2023-02-07 at 12 55 58 AM" src="https://user-images.githubusercontent.com/43849911/217065969-f0717407-8659-49d2-a19c-5a2781fc31ef.png">

<img width="1565" alt="Screenshot 2023-02-07 at 12 56 30 AM" src="https://user-images.githubusercontent.com/43849911/217066061-f5325d1d-1791-4ce0-8ee6-c03a3ca33d2e.png">

<img width="1436" alt="Screenshot 2023-02-07 at 12 57 33 AM" src="https://user-images.githubusercontent.com/43849911/217066247-d842d83e-7ac4-4dfb-b6cf-9d5b0624521b.png">

<img width="1492" alt="Screenshot 2023-02-07 at 12 57 48 AM" src="https://user-images.githubusercontent.com/43849911/217066290-ba45c830-2cbb-4b1e-b73b-567ce55d24c4.png">

<img width="1562" alt="Screenshot 2023-02-07 at 12 58 16 AM" src="https://user-images.githubusercontent.com/43849911/217066372-b60b512f-9691-4571-b736-fbbb1ca9a3d8.png">

<img width="1538" alt="Screenshot 2023-02-07 at 12 58 38 AM" src="https://user-images.githubusercontent.com/43849911/217066449-5998560f-3078-49c1-9993-cb93500c55d8.png">

<img width="1566" alt="Screenshot 2023-02-07 at 1 06 18 AM" src="https://user-images.githubusercontent.com/43849911/217067912-8b7b20c9-35ac-49c3-9f74-85297efa71d2.png">

<img width="1557" alt="Screenshot 2023-02-07 at 1 06 35 AM" src="https://user-images.githubusercontent.com/43849911/217067973-904c6bbd-a4d0-4be7-8f11-3d541690e0c0.png">

<img width="1561" alt="Screenshot 2023-02-07 at 1 07 02 AM" src="https://user-images.githubusercontent.com/43849911/217068061-22036a08-2ce5-490b-be18-784f82e9508b.png">

<img width="1561" alt="Screenshot 2023-02-07 at 1 07 33 AM" src="https://user-images.githubusercontent.com/43849911/217068149-2e3a116f-2437-4a66-a8ac-82ab1475cb92.png">

<img width="1558" alt="Screenshot 2023-02-07 at 1 36 03 AM" src="https://user-images.githubusercontent.com/43849911/217073935-d13596d2-cada-48e5-8d5e-1ddfe2a29fca.png">

dckr_pat_9SKIv1zmJYmHQ2LO_gdLSLsfbok

<img width="1558" alt="Screenshot 2023-02-07 at 1 38 14 AM" src="https://user-images.githubusercontent.com/43849911/217074254-a14bf03b-712a-4c0c-a740-e988ca77a362.png">

<img width="1556" alt="Screenshot 2023-02-07 at 1 38 42 AM" src="https://user-images.githubusercontent.com/43849911/217074334-a76341f8-8a4b-4dca-9452-708d85325324.png">

<img width="1305" alt="Screenshot 2023-02-07 at 1 40 20 AM" src="https://user-images.githubusercontent.com/43849911/217074659-07a973cf-9ba3-4e80-bcb4-7445b165bc1f.png">



