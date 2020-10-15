# nvim-python

Dockerized dev environment using neovim and language server protocol

- [x] LSP based autocomplete using pygls and lua completion-nvim
- [x] Treesitter based semantic highlighting
- [x] Tabnine based completions
- [x] Various convenience plugins
- [ ] Snippets
- [ ] reduce lag by autoimport

Build:
```
git clone <this repo>
cd <this repo>
docker build -t <img name> .
docker run -ti --rm <img name>
```

Launch neovim using `nvim`
Install plugins: `:PlugInstall` inside `nvim`

