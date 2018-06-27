# Plugin Managers

You'll find when you start using vim you'll want to install some handy plugins to enhance your workflow. To do this there are a number of different plugin managers you can use to handle these.

Here's a list of some popular ones:
- [Pathegeon](https://github.com/tpope/vim-pathogen)
- [Vim Plug](https://github.com/junegunn/vim-plug)
- [Vundle](https://github.com/VundleVim/Vundle.vim)
- [Volt](https://github.com/vim-volt/volt)

I recommend using either Vim Plug or Pathegeon, for no other reason than I've tried them both and liked them.

Today we're just going to use Plug for the examples.

## Installing a plugin manager
### Vim Plug
You can read more about the package manager here: https://github.com/junegunn/vim-plug

To install you just need to run this:
Linux:
```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

This will download [plug.vim](https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim) and store it in your autoload vim folder.
