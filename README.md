# aws-vault

This plugin provides support for [aws-vault](https://github.com/99designs/aws-vault). Currently this means that the login keychain is set as the one that aws-vault will use.

To use it, add `aws-vault` to the plugins array in your zshrc file.

```zsh
plugins=(... aws-vault)
```
