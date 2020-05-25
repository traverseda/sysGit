# sysGit
I manage server configuration via GIT, as per this article on dotfilts: https://medium.com/toutsbrasil/how-to-manage-your-dotfiles-with-git-f7aeed8adf8b

## Quickstart

```bash
wget https://github.com/traverseda/sysGit/raw/master/gsys.sh -P /usr/bin/ #Add gsys management tool
chmod +x /usr/bin/gsys.sh
gsys.sh config --local status.showUntrackedFiles no #Way too many files otherwise
git clone --bare https://github.com/traverseda/sysGit.git
gsys.sh checkout raidArray #Or whatever box this is actually on...
```
