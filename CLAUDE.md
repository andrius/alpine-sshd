# CLAUDE.md

Alpine SSHD server / jump box with lshell-jailed users, autossh and sudo. Own repo (Andrius).

- Base: `andrius/alpine-lshell:latest` (from this collection); exposes port 22.
- Ships `ssh_config`, `sshd_config`, `lshell.conf`, and key generation via `generate-keys.sh`.
- Run through `docker-compose.yml`; users defined under `sshuser/`.
- Last commit: 2018-11-03.
