#### Set up VIM as an IDE

Vim is a text editor is a highly configurable text editor for efficiently creating and changing any kind of text. It is included as "vi" with most UNIX systems and with Apple OS X.

Vim is the goto text editor for most developers due to the fact that it is light weight and is compatible with almost all computing plaforms (there is a version for windows)

###### Steps in setting up vim

- To install vim on ubuntu or any other system that user apt package manager simply enter the following command:

  `sudo apt-get install vim`

- Once vim is installed head over to [github](https://www.github.com/) and download the .vimrc file 

- Copy the .vimrc file to your home directory. (use cd command and hit enter to navigate to your home directory)

- Run the following command to install [vunde](https://github.com/VundleVim/Vundle.vim) which is a plugin manager for vim (Vundle stands for vundle)

  `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

- Once vundle installion is complete open vim on the command line using the `vim` command

- Now to install the plugins referenced in the .vimrc file you need to run the PluginInstall command (press esc to enter command mode in vim the press '':'' and type PluginInstall). Installing all the plugins will take a few moments

- After installing the plugins, exit vim (use esc the :q to quit)

- open vim once again and all the plugins should be installed. To open the file tree use ctrl+T

