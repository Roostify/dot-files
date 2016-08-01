# Dotfiles
In order to make our lives a teeny-tiny bit more consistent, useful shared dotfile stuff will be added here.

## Usage

1. Install homeshick https://github.com/andsens/homeshick
2. Clone this repo with homeshick: `homeshick clone git@github.com:Roostify/roostify-dotfiles.git`
3. Symlink these via: `homeshick link roostify-dotfiles`
4. Add `source $HOME/.roostify/bash_profile` to `~/.bash profile`.
5. Add `source $HOME/.roostify/bash_profile_extensions/<file_name>` for each of the extensions you're interested in.
6. Profit?

### Programs + Aliases

#### `subl`
Symlink to `/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl` for those with sublime installed.

#### `roostify-bootstrap-system`
Installs the programs you need to work on the majority of roostify projects. Useful to run this on a new machine.

#### `git-issues-between`
Given two branches, Lists github issues/pull requests in the format Org/repo#number. Useful for building release notes.
