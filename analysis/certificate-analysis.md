# Certificate Analysis

## Issuer
Let's Encrypt Authority X3

## Validity
90 days — short validity improves security.

## Key Type
RSA 2048 bits — acceptable but could be upgraded to 3072 or 4096 bits.

## SAN (Subject Alternative Names)
- example.com
- www.example.com

## Issues
- OCSP stapling not enabled
- No EV certificate (optional)

## Recommendations
- Enable OCSP stapling
- Consider RSA 3072 or ECDSA keys
