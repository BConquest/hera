# Hera
Hera is a two-column [Zola](https://github.com/getzola/zola) theme based on the [hyde theme](https://github.com/getzola/hyde).

## Installation
First download this theme to your `themes` directory:

```bash
$ cd themes
$ git clone https://github.com/BConquest/hera.git
```
and then enable it in your `config.toml`:

```toml
theme = "hera"
```

## Options

### Sidebar menu
Set a field in `extra` with a key of `hera_links`:
```toml
[extra]
hera_links = [
    {url = "https://google.com", name = "Google.com"},
    {url = "https://google.fr", name = "Google.fr"},
]
```
Each link needs to have a `url` and a `name`.

## Todo
- [ ] More Consistent Color Design/Style
- [ ] Add support for analytics
- [ ] Refactor to have sensible variable names
- [ ] Better Tag Support
