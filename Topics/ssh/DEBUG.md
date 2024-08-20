# Issue 1: Fix for SSH Permission Denied (Public Key)
To begin troubleshooting, first move into the ~/.ssh directory on your computer.

* Generate Public Key
```
ssh-keygen
```
Then write key name and enter and enter.

* Create config file and 
```
vim config
```
and write
```
IdentityFile ~/.ssh/key_name
```

* To confirm the private and public keys are a match, I can run the following command to examine the private key and see what the contents of the corresponding public key should be:

```
ssh-keygen -y -e -f key_name
```

* I can then output the contents of the public key (susans-macbook.pub) to make sure it’s a match:

```
cat susans-macbook.pub 
```
This key should be place in server Computer.

Till this point you have to do in your client Computer.

* Now, you have to write that key in "authorized_keys" file in your server Computer.

Then this issue may get resolved.




