# RC Forge

Project page for **rc-forge** — a programmatic modding toolchain for *Star Wars: Republic Commando*
(2005), the fourth in the forge family after [ER Forge](https://er-forge.vercel.app) (Elden Ring),
[KOTOR Forge](https://kotor-forge.vercel.app) and [AC6 Forge](https://ac6-forge.vercel.app).

A single static `index.html`. No build step, no dependencies — Vercel serves it as-is.

## What the page documents

- **Verified formats.** Every asset container's header measured directly off a retail install rather
  than taken from secondhand claims. Republic Commando's `.ctm` maps are ordinary Unreal packages
  (`0x9E2A83C1`, version 159, licensee 1), and the Karma `.ka`/`.kaw` physics files are plain XML.
- **Toolchain inventory.** SWRC Fix, the rebuilt `UCC.exe` and its 18 commandlets, the CT source
  tree, UELib, UE Explorer.
- **Architecture.** Four write surfaces ranked by blast radius, and why v1 needs no binary package
  writer at all.
- **A 13-item risk register**, researched before any code was written, with the mitigation for each.
- **Roadmap and open questions**, every unknown carrying the date it was last checked.

## Deploying

Import this repository into Vercel as a static project. No framework, no build command, output
directory is the repo root.

## Note on assets

This project ships code and documentation only. No extracted game assets are included or
redistributed — everything rc-forge does operates on the user's own installation. Star Wars and
Republic Commando are property of Lucasfilm / Disney; this is an unaffiliated fan project.
