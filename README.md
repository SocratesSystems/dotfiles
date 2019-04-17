My dotfiles and stuff I want to automate whenever I decide reformatting my machine is a good idea. Love that fresh OS Smell.

Shoutout to the following repositories:

* [18F/laptop](https://github.com/18F/laptop) - For providing the mac script I used to provision 
* [thoughtbot/laptop](https://github.com/thoughtbot/laptop) - For providing the original mac script 18F/laptop uses
* [prezto](https://github.com/zsh-users/prezto) - I will forever mispell this as pretzo

Setup for macOS:

1. Run setup script (installs homebrew, yadm, clones this repository and installs a bunch of brew items)
   ```
   curl -L https://raw.githubusercontent.com/SocratesSystems/dotfiles/master/bootstrap.sh | bash
   ```
2. Change shell to ZSH
   ```
   chsh -s /bin/zsh
   ```
3. Install tmux plugins

   1. Open tmux
       ```
       tmux
       ```

   2. Install plugins by pressing `Ctrl+B <let go> Shift+I` then **wait 30 seconds**.

   3. Close tmux by running `exit` in the shell
   
