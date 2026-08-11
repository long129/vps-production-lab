# Phase 01 — Troubleshooting Notes

## Incident 01 — SSH unavailable

### Symptom

The VM was reachable from the Windows host, but SSH remote access was unavailable.

Initial observations:

```text
Host -> VM ping: PASS
TCP/22: not listening
ssh.service: failed
