# Creating_SSH_KEYS
### ✅ open your terminal in MAC 👨🏻‍💻
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
#### ✌️this will create an SSH key ( you'll be giving the public key for authentication in apps private key will be saved in computer "give a good name" )
##### 👉🏻 it should be saved with ".pem" extension in MAC
### ✅ To display the SSH public key 
    cat ~/.ssh/id_rsa.pub     
#### 👉🏻 ".pub" here represents public key and id_rsa is my key name 
#### 👉🏻 this will display the key copy the whole key and use it where you want to
### ✅ you should add it to SSH agent so that you can use for that use below command
    ssh-add ~/.ssh/id_rsa
#### 👉🏻 this will add the key to agent 

