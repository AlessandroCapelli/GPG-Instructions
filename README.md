# GPG Instructions

## Download Public Key

[Alessandro Capelli's Public Key](https://github.com/AlessandroCapelli/GPG-Instructions/blob/main/PK.asc)

## Import Public Key

```
gpg --import PK.asc
```

## Verify fingerprint

```
gpg --fingerprint
```

### Check Fingerprint and Validity

```
58A7 F67B 3243 A08E C30A 46E5 7209 114B CF34 1715
```

## Encrypt and Sign

```
gpg --encrypt --sign --armor --recipient 'recipient email' <file>
```

## Decrypt and Verify

```
gpg --output <file> --decrypt <encrypted-and-signed-file>
```
