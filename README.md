# clj_clean_ns.vim

This simple script uses [vim-fireplace](https://github.com/tpope/vim-fireplace) to call Refactor nREPL's [`clean-ns`](https://github.com/clojure-emacs/refactor-nrepl#clean-ns)
operation, and replaces the current namespace declaration with the cleaned one.

This started out as an extraction of [vim-cider's `clean_ns` function](https://github.com/clojure-vim/vim-cider/) into a
working, separate, standalone file.

No longer in use.

## Usage

```vim
:CljCleanNS
```

## License

[MIT](./LICENSE.md)
