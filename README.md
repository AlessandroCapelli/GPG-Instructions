# GPG Instructions

## Import Public Key

```
gpg --import PK.asc
```

## Encrypt and Sign

```
gpg --encrypt --sign --armor --recipient 'recipient email' <file>
```

## Decrypt and Verify

```
gpg --output <file> --decrypt <encrypted-and-signed-file>
```
