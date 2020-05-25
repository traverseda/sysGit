# sysGit
I manage server configuration via GIT, as per this article on dotfilts: https://medium.com/toutsbrasil/how-to-manage-your-dotfiles-with-git-f7aeed8adf8b

## Quickstart

```bash
wget https://github.com/traverseda/sysGit/raw/master/gsys.sh #Add gsys management tool
chmod +x ./gsys.sh
./gsys.sh config --local status.showUntrackedFiles no #Way too many files otherwise
git clone --branch <branchname> --bare https://github.com/traverseda/sysGit.git /root/sysImage
./gsys.sh checkout #To actually add the files to your system image, this also installed gsys.sh to `/usr/bin/gsys.sh`
```
