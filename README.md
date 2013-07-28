dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `bash` and `vim` development environment as follows:

```sh
cd $HOME
git clone https://github.com/untidy-hair/dotfiles.git
ln -sb dotfiles/.tmux.conf .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
ln -sb dotfiles/.vimrc .
ln -sb dotfiles/.jshintrc .
```

See also http://github.com/untidy-hair/setup to install prerequisite
programs. If all goes well, in addition to a more useful prompt, now you can
do `vi hello.js` and hitting `C-c!` to launch an interactive SSJS
REPL, among many other features. See the
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.
