# buildHabitat

#### By _**BeatGrate**_

## Technologies Used
1. Ansible


## Description
What does buildHabitat do? Adds the following modifications to your shell:
1. Installs and configures a whole bunch of cool sh\*t:
    1a. zsh (a more customizable shell):
        - oh-my-zsh (a framework that allows for zsh customization)
        - Powerlevel10k (the only zsh theme that matters)
        - zsh-autosuggestions (like iPhone predicitve text but for your shell)
        - zsh syntax-highlighting (You know... syntax highlighting)
        - zsh-z (allows you to jump to frequently visited directories using z <location>)
    
    1b. vim (Needs no introduction)
    
    1c. tmux (Lets you open multiple terminal windows in a single window)
        - tpm (lets you install tmux plugins)
    
    1d. nala (waaaay cooler than apt)
    
    1e. tldr (like a man page but not confusing)
    
    1f. trash-cli (let's you recover deleted files)
    
    1g. progress (gives you a progress bar for things that usually don't show one)

2. Changes the default shell to zsh

3. Copies and sources various config files with all the bells and whistles:
    3a. .zshrc (some custom aliases, autostart tmux, makes it so rm uses trash-cli to let you recover deleted files)
    
    3b. .p10k.zsh (has cool ASCII art as the terminal header)

    3c. .vimrc (Has some optimizations for yml and python)

    3d. .tmux.conf (prefix-h for new horizontal terminal window, prefix-v for new vertical terminal window, and some other stuff)


## How to operate
1. Make sure you have Ansible installed on your machine, and run the following commands:
2. git clone https://github.com/BeatGrate/buildHabitat.git
3. cd buildHabitat
4. ansible-playbook -K buildHabitat.yml
5. Enter your password and enjoy!

## Setup

## Known Bugs
