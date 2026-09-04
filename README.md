# syn-remote

Remote desktop for SynapseOS — wayvnc, with the screen woken and held awake while somebody is connected

## Install

```bash
git clone https://github.com/velle999/syn-remote
cd syn-remote && makepkg -si
```

makepkg fetches the source for this PKGBUILD's exact version from this
repository's releases, so a clone can only ever build the source it was
written against. `.SRCINFO` lists what it needs.

## Where this comes from

Developed in [the SynapseOS monorepo](https://github.com/velle999/SYNAPSE),
in `syn-remote/`. **This repository is generated from it** — the PKGBUILD, a
generated `.SRCINFO` and this README — so issues and patches belong there.

syn-remote 0.1.0-1 · GPL-2.0-or-later
