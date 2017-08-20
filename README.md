# atom-haskell package

Curated set of packages for Haskell development with Atom. The package list taken from [Atom-Haskell Documentation](https://atom-haskell.github.io) (not made by me :). Configuration, documentation and much more can be found there.

This package installs the following for you:

- [language-haskell](https://atom.io/packages/language-haskell) – Syntax highlighting and Haskell autodetection
- [ide-haskell](https://atom.io/packages/ide-haskell) – GUI and minimal utilities
- [ide-haskell-cabal](https://atom.io/packages/ide-haskell-cabal) – Build Haskell projects with either cabal or stack. Reports errors/warnings on build.
- [haskell-ghc-mod](https://atom.io/packages/haskell-ghc-mod) – ghc-mod integration. Typecheck and lint sources without building, query type information and more.
- [autocomplete-haskell](https://atom.io/packages/autocomplete-haskell) – Autocompletion support. This plugin depends on haskell-ghc-mod.
- [haskell-pointfree](https://atom.io/packages/haskell-pointfree) – convert selection to pointfree/pointful representation
- [ide-haskell-hasktags](https://atom.io/packages/ide-haskell-hasktags) – go to declaration, list all symbols defined in file/project
- [ide-haskell-hoogle](https://atom.io/packages/ide-haskell-hoogle) – lookup hoogle documentation via local hoogle database
- [ide-haskell-repl](https://atom.io/packages/ide-haskell-repl) – GHCi REPL in Atom
- [language-haskell-scoped](https://atom.io/packages/language-haskell-scoped) – highlight known identifiers in editor
- [atom-hasklig](https://atom.io/packages/hasklig) throws in the nice Hasklig font

Additionally it installs,

- [linter-hlint](https://atom.io/packages/linter-hlint)
- [linter-hdevtools](https://atom.io/packages/linter-hdevtools)

which you can optionally disable.

# Binaries

To set up the binaries (except formatters) for the above you can run,

```bash
stack install ghc-mod hoogle hasktags pointfree pointful cabal-install
```

For formatters you have some choice between `stylish-haskell`, `hindent` and `brittany`, whichever you prefer. E.g.,

```bash
stack install hindent
```

# Other things

Finally, a bit of a self-plug, but I recommend the theme [Spacemacs Dark](https://github.com/Tehnix/spacemacsdark-syntax-atom), where I added some additional highlighting for Haskell. It is, as the name implies, inspired by the Spacemacs dark theme.

![Screenshot of Spacemacs Dark Syntax](https://user-images.githubusercontent.com/1189998/29494933-b0e81f7a-85ef-11e7-8359-8550f32d6760.png)
