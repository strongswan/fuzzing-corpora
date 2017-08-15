# strongSwan Fuzzing Corpora
Corpora for fuzzing parts of the strongSwan code base

- **certs**: X.509 certificates, initially 1000 files, half of them in DER and half of them im PEM format (obtained from certificate-transparency.org)
- **certs-crash**: Input generated while fuzzing that caused crashes (or timeouts etc.)

The name of every file is the SHA-256 hash of its contents.
