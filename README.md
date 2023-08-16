# vimSetup
my vim setups

# Download the main file
```
cd .
git clone git@github.com:remichassagne/vimSetup.git .vim
```

# Download Pluggins
Create and go into the plugged directory:
```
cd .vim
mkdir plugged
cd plugged
```
Download pluggins
```
git clone git@github.com:dense-analysis/ale.git
git clone git@github.com:preservim/nerdtree.git
git clone git@github.com:cburroughs/pep8.py.git
git clone git@github.com:nvie/vim-flake8.git
```

# Finalize installation
Copy the vimrcFile as .vimrc:
```
cd ~/.vim/
cp vimrcFile ../.vimrc
```
Open the .vimrc file with vim:
```
cd ../
vim .vimrc
```
and enter the following vim commands:
```
:source ~/.vimrc
:PlugInstall
```
