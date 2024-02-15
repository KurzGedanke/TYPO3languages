**Typo3Languages** provides syntax highlighting and autocompletion for TypoScript & TSConfig.

## Language Support

Typo3Languages currently supports the following features of Languages:

- .typoscript
- .tsconfig

## Acknowledgement

Thanks very much to [Teddytrombone](https://github.com/Teddytrombone/tree-sitter-typoscript) for the typoscript tree-sitter!

## Compile for yourself

Clone the tree-sitter form teddytrombone into another directory which is not in the extension

```sh
$ git clone git@github.com:Teddytrombone/tree-sitter-typoscript.git
```

copy the `Makefile` into the `/tree-sitter-typoscript` and

```sh
$ tree-sitter generate
```

