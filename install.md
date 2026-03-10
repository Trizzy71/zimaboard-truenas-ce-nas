# Step-by-step on my installation of TrueNAS CE
## Sourcing TrueNAS CE
- You can find the TrueNAS insatllation files at:
   - https://www.truenas.com/download/
   - (Don't hesitate to support the company!)
- If you need a specific version:
   - https://www.truenas.com/docs/softwarestatus/

## Creating your installation media
- BalenaEtcher for a live USB
   - Balena Git: https://github.com/balena-io/etcher
- I will be copying the ISO to a USB drive where I already have Ventoy installed.
- *It probably isn't the optimal install method but I think Ventoy is cool and you should, too.*
   - Ventoy Git: https://github.com/ventoy/Ventoy

## BIOS settings for Zima
- Boot Mode: UEFI
- SATA Mode: AHCI
- Boot Order: USB first
