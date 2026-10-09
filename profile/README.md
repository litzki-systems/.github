# Litzki Systems LLC

## Sovereign Validation Protocol (SOVP)

SOVP is a protocol for checking, before ingestion, that a signed identity document was
produced by the holder of the Ed25519 key published in DNS for a host.

Specification: IETF Internet-Draft
[draft-litzki-sovp-04](https://datatracker.ietf.org/doc/draft-litzki-sovp/) — Individual
Submission, Intended Status: Experimental.

## Verdicts

The SOVP scanner reports one of three verdicts: **CERTIFIED**, **NOT_CONFORMANT** or
**INCOMPLETE**. INCOMPLETE means the host could not be measured, for example because
access was blocked during the scan — it is not a statement about the host's quality.

Verdicts are reported in the scan result. They are not part of the signed identity
document.

## Implementations

- [sovp-python](https://github.com/litzki-systems/sovp-python) — reference
  implementation, Apache 2.0 (PyPI: [`sovp`](https://pypi.org/project/sovp/))
- [sovp-agentrust-bridge](https://github.com/litzki-systems/sovp-agentrust-bridge) —
  maps caller-supplied fields onto an Ed25519-signed AgenTrust TRACE v0.2 record,
  Apache 2.0

## Services

- Free QuickScan: https://validator.litzki-systems.com
- Full Validator: https://litzki-systems.com/sovp-full-validator
- Company and protocol: https://litzki-systems.com

## Contact

https://litzki-systems.com/contact

---

Patent Pending — U.S. Provisional Patent Application No. 64/005,737
© 2026 Litzki Systems LLC
