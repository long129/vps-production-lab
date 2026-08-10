# Phase 00 — Workstation & Git Baseline

## Objective

Prepare MobaXterm as the primary administration terminal and establish a working Git/GitHub SSH workflow.

## Implemented

- MobaXterm local Bash shell verified.
- Git availability verified.
- OpenSSH availability verified.
- Git global identity configured.
- `~/.ssh` directory prepared.
- ED25519 SSH key pair generated.
- Private/public key permissions configured.
- GitHub host recorded in `known_hosts`.
- Public key registered with GitHub.
- SSH authentication to GitHub verified.
- `vps-production-lab` cloned using SSH.
- First repository artifact created.
- First Git commit created.
- `main` successfully pushed to GitHub.
- Remote repository content verified.

## Git Identity

Git commits are configured with:

- Username: `long129`
- Email: configured locally

The email value is intentionally not documented here as it is not required to demonstrate the lab.

## SSH Files

```text
~/.ssh/
├── id_ed25519       # Private key — never commit
├── id_ed25519.pub   # Public key
└── known_hosts      # Known SSH server identities

