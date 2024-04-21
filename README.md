# minifuzzy.vim :mag_right:
## A Cross-Platform Vim9 Fuzzy Finder

FdMinifuzzy is an oxidized fork of the original Minifuzzy, a Vim9Script fuzzy finder. FdMinifuzzy leverages the power of the *fd* command, written in Rust, to ensure seamless compatibility across various platforms.
FdMinifuzzy honors the rules specified in your project’s .gitignore file, ensuring that excluded files and directories are respected during fuzzy searches.

![Using minifuzzy.vim to search files in the current directory](images/minifuzzy.gif)

## :hammer: Installation
:warning: Only supported for vim >= 8.2, not nvim

[Required *fd* binary in the PATH](https://github.com/sharkdp/fd/releases/tag/v9.0.0)

Install using vim's plugin manager:
```sh
Plug 'sevehub/fdminifuzzy'
```

## :alembic: Usage
The following mappings can be used to fuzzy find:
- `<leader>ff` -- Files in current working directory
- `<leader>fb` -- Buffers
- `<leader>fm` -- Most recently used files
- `<leader>fl` -- Lines in the current buffer

---
