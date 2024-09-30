# Transcrypt Testing Repository

This repository is created to test and demonstrate the functionality of [Transcrypt](https://github.com/elasticdog/transcrypt), a transparent encryption tool for Git. The goal of this project is to provide a sandbox environment to explore how to secure sensitive files within Git repositories using Transcrypt.

## About Transcrypt

[Transcrypt](https://github.com/elasticdog/transcrypt) is a transparent encryption tool for Git repositories, enabling the encryption of specific files in a project while allowing the rest to remain unencrypted. It uses GPG to encrypt and decrypt files during Git commits and checkouts, ensuring that sensitive data remains protected while still maintaining version control.

`secret_starship.json` is encrypted using transcrypt. To decrypt it, you need to have the transcrypt key. If you have a key, transcrypt will automatically decode file after pull.
Any new file put in `vcr` directory will be automatically encripted before push. No other commands required.



### [Some other alternatives](https://medium.com/@slimm609/securely-storing-secrets-in-git-542771d3ed8c)
