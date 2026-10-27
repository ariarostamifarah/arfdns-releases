# arfdns-releases

Signed server releases for ArfDNS. Each GitHub release here is one version: `manifest.json`
(signed with the offline release key) and the `arfd-linux-*` binaries it lists.

Servers download a binary from
`https://github.com/ariarostamifarah/arfdns-releases/releases/download/<version>/<file>` and
install it only if its SHA-256 matches the signed manifest, so a copy from anywhere else is
equally safe to use.
