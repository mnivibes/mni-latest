# mni-latest

The latest approved MNI 1 Plus firmware, as data only (D-285): `approved.json` lists the approved suit and TX
versions, their release tags, commits and dates. No firmware and no code are here.

MNI field update kits read
`https://raw.githubusercontent.com/mnivibes/mni-latest/main/approved.json` when they start, to tell a technician
when a newer kit exists. The file is written by the `approved-pointer` GitHub Action of the private firmware repo
on every `approved/suit-X.Y.Z` tag; do not edit it by hand.
