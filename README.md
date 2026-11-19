# mni-latest

The latest approved MNI 1 Plus firmware, as data only (D-285): `approved.json` lists the approved suit and TX
versions, their release tags, commits and dates, and since 2026-11-18 each release's firmware images (the
suit and transmitter update files, with their SHA-256), which are this repo's release downloads. No source code is here.

MNI field update kits read
`https://raw.githubusercontent.com/mnivibes/mni-latest/main/approved.json` when they start, to tell a technician
when a newer kit exists. The file is written by the `approved-pointer` GitHub Action of the private firmware repo
on every `approved/suit-X.Y.Z` tag; do not edit it by hand.

VibroDJ reads the same file for its firmware update (Settings): it compares the suits and the transmitter with
`latest`, downloads the files `latest.files` names and checks their SHA-256 before anything is sent.
