# PQS stable release metadata

This repository contains only digitally signed metadata for owner-accepted stable
PQS application releases. Application source and packages remain private.

Clients verify the P-256 ECDSA/SHA-256 DER signature with their pinned public key,
then validate release identity, version, expiry and replay protection. TLS or tag
names alone do not establish approval. Metadata never downloads or installs PQS.

PQS 5.0 is the accepted application currently described by stable.json.
PQS 5.1 is a development candidate and is not an approved update.

Refresh and publication are owner-authorized manual operations. Expired,
unavailable or invalid metadata must produce an unavailable status.
