# iTerm2

Configure iterm2 to reuse session directory instead of home directory, when opening a new tab.

To do 

> iTerm2 -> Preferences

In Profile tab, choose **Reuse previous session's directory** under **Working directory**

<img width="902" alt="new tab" src="https://user-images.githubusercontent.com/1156953/55868466-2c71dd00-5ba2-11e9-8a7e-ae8a801f0283.png">

## Alias

Set the `alias` for IDE in `.` files.

    alias as='studio'
    alias ws='webstorm'
    
If you're using normal termial, you need to set that in `~/.bash_profile`. If you're using Zshell, set the configs in `~/.zshrc`
