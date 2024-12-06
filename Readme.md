# UltraAtomic 

UltraAtomic is a theme forked from main OhMyPosh repository ([here](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/atomic.omp.json)).


## Installation

1. Create a directory in your home folder (or wherever you want)
    ``` sh
    cd ~
    mkdir OhMyPosh
    cd OhMyPosh
    ```
2. Download the UltraAtomic.json file
    ``` sh
    git clone https://github.com/anndreiAbabei/UltraAtomic.git
    ```
3. Open your `.zshrc` (if you're using zsh)
    ``` sh
    nano ~/.zshrc
    ```
    And find the line with oh my posh configurtion
4. Edit the line to include the theme
    ``` sh
    eval "$(oh-my-posh init zsh --config ~/OhMyPosh/UltraAtomic/UltraAtomic.json)"
    ```
    Save and exit with `CTRL+O` and then `CTRL+X`
5. Restart your shell
    ``` sh
    . ~/.zshrc
    ```
