# Vaults

To support a wide variety of platforms `libwallet` has the concept of a vault, 
an abstraction used to retreive private for signing.

### Simple
An in memmory key storage that will forget keys at the end of a program's execution. It's useful for tests and generating addresses.

### OS Keyring
A cross platform storage that uses the operating system's default keyring to store the secret seed used to generate accounts. Useful for desktop wallets.