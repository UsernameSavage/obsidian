
#### GPG-Key
configure GPG Key to your git: https://wiki.bedag.ch/x/9QAZDw
`gpg --list-keys --keyid-format LONG` 
`git config --global user.signingkey $KEY_ID
your `.gitconfig` file should look like this:
```gitconfig
[user]
	email = aro.ibrahim@bedag.ch
	name = Ibrahim Aro
	signingkey = D763860269B22301
[init]
	templateDir = /home/aib/.git-template
[commit]
	gpgsign = true

# [format]
#        signOff = true
```
your GPG key should also be in your git profile:
![[Pasted image 20231121111805.png]]
#### Git
- git clone repo to your local
- make the changes 
- `git add .`
- `git status` to make sure your changes are correct
- git commit, example: git commit -am "chore: Javacar Abbau" -s <!-- s=signoff>