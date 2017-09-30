Syntax highlighting for Splunk's .conf files
=============

This project is public domain. Feel free to create your own branch and submit a pull request via Github or email me: colbyw at gmail dot com.

Thanks to the many contributors to this project.

The 7.0 branch utilizes pattern matching to ensure proper keyword spelling and placement. In an effort to reduce CPU overhead, the majority of .conf file associations were moved from a monolithic .vim file to a set of federated .vim files, one .vim per .conf(.spec).

![props.conf example with solarized colour scheme](http://i.imgur.com/F0rVkzt.png)

Installation Instructions
=============

You can either clone the repository somewhere on your file system and use symlinks to the corresponding directories or clone to `~/.vim/bundle` as a submodule.

Symlink instructions:
```
mkdir ~/git-projects
cd git-projects
git clone git@github.com:yorokobi/vim-splunk.git
ln -s git-projects/vim-splunk/ftdetect/splunk.vim ~/.vim/ftdetect/splunk.vim
ln -s git-projects/vim-splunk/syntax/splunk.vim ~/.vim/syntax/splunk.vim
```
Bundle instructions:
```
cd ~/.vim/bundle
git clone git@github.com:yorokobi/vim-splunk.git
```
Submodule instructions:
```
cd ~/your/vim/bundle/repo
git submodule add git@github.com:yorokobi/vim-splunk.git
git commit -am "Added vim-splunk as a submodule"
```
