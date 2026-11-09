# REVIEW_NEEDED — Issue #10 (open sea split)

Per `decisions.openSeaSplit`, species are not reclassified until the owner has a
reproducible distance-from-shore share for each one.

## Blocked on the committed tool

`sea-shares.tsv` from the 2026-11-08 run was not committed. Only four shares are
recorded in `river/notes.md`. The new column in `data/habitat-review.tsv` stays
blank for every species until a committed tool produces it.

## Cannot be separated by the share

The 10 km share cannot tell a bird standing on the beach from a bird in the surf;
shore records are logged just past the coastline. These stay blank:

- **Gulls & kittiwakes:** Western, Laughing, Kelp, Yellow-footed, Ivory,
  Black-legged Kittiwake, Red-legged Kittiwake.
- **Terns & noddies:** Common, Least, Royal, Sandwich, Roseate; Brown, Black,
  Blue-gray, Blue-billed White, Sooty, Bridled, Gray-backed.
- **Sea ducks & eiders:** Common, King, Steller's Eider; Harlequin Duck.
- **Unverified alcids:** Common Murre, Thick-billed Murre, Kittlitz's Murrelet.

## Do not change in this PR

- Column 3 of `data/habitat-review.tsv` (AVONET verbatim).
- `trait.Habitats` (AVONET vocabulary only).
- The "Shore and sea" group selector.