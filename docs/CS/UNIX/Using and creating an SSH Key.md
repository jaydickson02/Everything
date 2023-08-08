
You do not need to make a new key for each server connection, one key is used per accessing computer. This key is stored on the device and can be used for multiple connections.

---
## Creating a key

First create the ssh key on the connecting device with:

	ssh-keygen -t rsa

\# *-t specifies type of key in this case rsa*

- You can add a parse-phrase which ensures a hacker can't use your key immediately. This has the downfall that you have to type the passphrase in each time you connect.

### On MAC:

*Key is saved in /Users/USER/.ssh/id_rsa*

### On Unix:

Key is saved in /home/USER.ssh/id_rsa

---
## Copying the key to a server

### Access the key to copy as plaintext:

	cat /Users/USERNAME/.ssh/id_rsa.pub

\# Copy this output to digital ocean or other hosting platform

### Add to server from command line:

If ssh-copy isn't already installed run:

	brew install ssh-copy-id

\# *On MAC*

To copy to server run:

	ssh-copy-id USER@IP-ADDRESS