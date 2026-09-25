# TLS Hardening Recommendations

## Disable Legacy Protocols
- Disable TLS 1.0
- Disable TLS 1.1

## Enforce Strong Cipher Suites
- Allow only TLS 1.2 and TLS 1.3
- Remove SHA1-based ciphers

## Enable Security Features
- Enable HSTS (HTTP Strict Transport Security)
- Enable OCSP stapling
- Enable certificate transparency

## Improve Key Strength
- Use RSA 3072+ or ECDSA keys

## Summary
Implementing these changes significantly improves HTTPS security posture.
