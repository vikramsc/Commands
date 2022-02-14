## passwordless from source to dest

1. On **source**, Generate public key using ssh-keygen
2. On **source**, cat ~/.sshd/id_rsa.pub and copy the content
3. On **dest**, append the above copied content to ~/.ssh/authorized_keys
4. Now you can ssh user@dest from source host without password


## Password as argument

1. Install sshpass
2. sshpass -p <passwd> ssh -o StrictHostKeyChecking=no user@dest.com
