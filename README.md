# strongSwan Fuzzing Corpora
Corpora for fuzzing parts of the strongSwan code base

- **certs**: X.509 certificates, initially 1000 files, half of them in DER and half of them im PEM format (obtained from certificate-transparency.org)
- **certs-crash**: Input generated while fuzzing that caused crashes (or timeouts etc.)
- **crls**: X.509 CRLs, initially 190 files in DER format, four in PEM format, one empty and five HTML error pages (obtained from certificates from certificate-transparency.org)
- **ids**: Identification strings/blobs, initially 21 identities from the strongSwan unit tests.
- **ocsp_req**: OCSP requests, initially 2 files in DER format derived from the strongSwan KVM regression tests.
- **ocsp_rsp**: OCSP responses, initially 4 files in DER format derived from the strongSwan KVM regression tests.
- **pa_tnc**: RFC 5792 PA-TNC messages, initially 18 messages derived from the strongSwan KVM regression tests.
- **pb_tnc**: RFC 5793 PB-TNC batches, initially 6 batches derived from the strongSwan KVM regression tests.

The name of every file is the SHA-256 hash of its contents.
