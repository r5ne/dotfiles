# dotfiles
---
jobless dotfiles for a jobless CS major
## Usage
- Clone the repo.
- Symlink `.stowrc` into your `$HOME` directory.
- Run `stow [package name]` if the package has no OS specific dots and `stow --dir=$HOME/dotfiles/package [os specific subpackage]` if there are.
## Format
- A new directory for each modular dotfiles I will want to use (usually translates to one program)
- A subdirectory for the OS used if there are parts of the dots that are OS specific
## Credits
- [monoglow.nvim](github.com/wnkz/monoglow.nvim) - for the colorscheme used by most of my dots
- [gnu stow](https://www.gnu.org/software/stow/) - for the best modular dotfile manager
