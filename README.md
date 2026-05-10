# nvim-config

My personal Neovim config based on NvChad.

## System dependencies

```bash
sudo pacman -S clang tree-sitter
```

- **clang** — provides `clangd` (LSP) and `clang-format` (formatter) for C
- **tree-sitter** — required to compile treesitter parsers

## Install

```bash
git clone https://github.com/1Ricc/nvim-config.git ~/.config/nvim
nvim  # plugins install automatically via Lazy
```