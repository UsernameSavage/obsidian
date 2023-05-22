Create Keys:  `ssh-keygen`   name e.g: id_rsa_github
Edit config file: `~/.ssh/config   
File:
`Host github.com    
	`IdentityFile ~/.ssh/id_rsa_github`

Reboot
`mkdir test
Create a repository test in github and clone with ssh
Terminal: Go to the `test` folder and type in git clone `ssh key`
`ssh-keygen` 
`cat .ssh/id_rsa.pub`
Copy ssh key and add to Github Settings
git clone `repository`
