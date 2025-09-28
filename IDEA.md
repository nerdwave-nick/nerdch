# Nerdwave Arch System
## Brainstorming
What do we want to solve?
- Only starting line - no long term support. Just a kickstart
- Hyprland setup, with the most basic functionality set up
    - lock screen
        - timeout, password, etc.
    - idling
        - screensaver?
    - power modes
        - battery, cpu, etc.
    - basic waybar
        - time
        - workspaces
        - wifi
        - system tray
        - bluetooth
        - audio
- Basic utilities set up
    - terminal (ghostty)
    - basic browser (zen?)
- theme support similar to omarchy
    - define the "interface" (the files that make up the themes for different applications) and a process to switch them (symlink folder)
- some basic keybinds (all in one file, no application specifics, just terminal, and some examples)
- wofi/drun, menu
- any other basic utilities (screenshotting, etc.)



- having an "interface" for packages/systems (similar to themes) on top
    - set up "your own" shit on top. This is where the current "bloat" goes
    - kickstarter itself only really has the most basic shit 
        - infrasturcture setup

*Don't make the game, make the engine*

## What would we need from the kickstarter?
- boot -> starting into hyprland
    - plymouth + limine, similar to omarchy
    - runner for custom packages
- optional packages, which integrate with the default supplied infra
    - waybar
    - basic terminal
    - basic editor
    - configuration for something like gtk theme etc.
- user packages, which can use the supplied infrastructure


### Hands off, one and done, kickstart your environment, and then go the arch way. Not "this is your system" but instead "this is how you probably won't wanna kill yourself"
