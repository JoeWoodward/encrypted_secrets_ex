# Changelog

## 0.2.0

- Changed default secrets location from `config/secrets` to `priv/secrets`
  - This will break existing installations, but you only need to move the files from `config/` to `priv/`
- Added ability for `setup` to append the master key location to your `.gitignore`
- Added documentation for Distillery releases
- Improved documentation and README

## 0.1.2

- Fixed bug where whitespace would break encryption/decryption

## 0.1.1

- Removed ExCrypto in favour of using Erlang functions
- Added information, caveats to README
- Added ability to specify key when editing secrets

## 0.1.0

Initial release!

- Added mix tasks for setup and editing
- Added core functions for reading and writing of encrypted secrets
