# System Configs

This repo contains various files I use across my Macs, the idea being that I keep them the same regardless of which device I am on to smooth out my workflows.

- [Brewfile](Brewfile) is created by using the [`brew bundle dump -f`](https://docs.brew.sh/Manpage#bundle-subcommand) command to output all the bundles installed on my Mac (`-f` forces it to override the existing file). I can easily install them on a new/another Mac with `brew bundle install`. 
    - I used the `--describe` flag to add the annotations to each bundle. 
    - This does not include ruby dependencies, unlike [`brew list`](https://docs.brew.sh/Manpage#list), but it does allow for easy "syncing" (relatively so), between Macs.
- [Git Config](.gitconfig) contains a few things particular to my system, one of which is I prefer to clone via ssh rather than https (as it always uses my ssh key). I also use the excellent [Kaleidoscope](https://kaleidoscope.app) application to diff and merge. (Please note, I am a professional software developer so for me this tool makes sense. The merge tools built into [Fork](https://git-fork.com) and other git clients are great too.)
- [Zsh](.zshrc) is my zsh config. I switched to zsh when macOS switched, and have improved my set up with the wonderful [Oh My Zsh](https://ohmyz.sh). 
