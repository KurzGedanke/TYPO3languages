**TYPO3Languages** provides syntax highlighting for TypoScript & TSConfig.

## Language Support

TYPO3Languages currently supports the following features of Languages:

- .typoscript
- .tsconfig

## Acknowledgement

- Thanks very much to [Teddytrombone](https://github.com/Teddytrombone/tree-sitter-typoscript) for the typoscript tree-sitter!
- Thansk to Panic Inc. for the compile_parser.sh and Makefile

## Compile for yourself

Clone the tree-sitter form teddytrombone into another directory which is not in the extension

```sh
$ git clone git@github.com:Teddytrombone/tree-sitter-typoscript.git
```

copy the `Makefile` into the `/tree-sitter-typoscript` and

```sh
$ tree-sitter generate
```
To be written...
