#FASTBuild

[![Join the chat at https://gitter.im/inbilla/fastbuild](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/inbilla/fastbuild?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

##Branch policy

| Branch | Purpose |
| :----- | :----- |
| master | Stable branch containing snapshot of latest release |
| dev    | Development branch for integration of pull requests |
 
Patches will only be accepted into the "dev" branch.**

## Change Integration

The canonical repo for FASTBuild is in perforce. Patches accepted into "dev" will be integrated into this Perforce depot.
When a new version is released, the stable (master) branch will be updated with a snapshot of the new released version.

"dev" -> Perforce -> "master"
