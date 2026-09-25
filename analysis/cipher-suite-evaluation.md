# Cipher Suite Evaluation

## Secure Cipher Suites
- TLS_AES_256_GCM_SHA384 (TLS 1.3)
- ECDHE-RSA-AES256-GCM-SHA384 (TLS 1.2)

## Weak Cipher Suites
- ECDHE-RSA-AES128-SHA
- AES256-SHA

## Issues
- TLS 1.0 and TLS 1.1 enabled
- Weak ciphers allowed

## Recommendations
- Disable TLS 1.0 and TLS 1.1
- Remove SHA-based cipher suites
- Prefer TLS 1.3-only configuration

