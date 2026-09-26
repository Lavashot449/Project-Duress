# September 25, 2026: Resonance preservation and Duress rebuild

## Inspection before substantive edits

The renamed remote was `https://github.com/Lavashot449/Project-Duress.git`, with default branch `main` at `03eed4a9dea9e2850163f7aa4e3952cf2d051684`. The existing local checkout matched that commit and was clean, with no untracked or ignored files. Its origin still used the former Project-Resonance URL; the local remote URL was updated to Project-Duress.

The original tree contained 68 tracked files: root navigation, attribution and contribution pages, editing instructions and attributes, three Book mirrors, canon, causality, character and continuity material, cosmology, Echoes, Exotics, historical sources, source manifests, and subclasses. No Post-Drowning active structure was present.

The inspection findings and preservation plan were reported to the author before restructuring.

## Preservation sequence

1. Created an empty checkpoint commit `b16c7ef4dc3abe3d1a6f689c4f544c9c2517d692`, retaining the original tree.
2. Created the annotated tag `pre-duress-resonance-2026-09-25` and published it together with the checkpoint before moving files.
3. Moved every tracked project file under the exact directory name `What Was Resonance`.
4. Verified that the staged archive subtree equaled the checkpoint's complete tree, including Git object identities and modes.
5. Committed the archive separately as `7a2e1c0b666108196589ed287d96c82211d0490d`: 68 exact renames, zero content insertions/deletions.
6. Built active root pages from D01, keeping the archive unchanged.

Original and archived tree identity: `c1222617d7d136dd46491ed1be185810b1c641fe`.

## Editorial decisions

- Current Post-Drowning foundation is recorded separately from historical Resonance.
- The new root editing instructions follow the current author directive. Archived instructions remain intact inside the historical project.
- Caveman QA remains explicitly non-canonical.
- Weight of Consequence and THE DEEP COLLAPSES INWARD retain their limited candidate statuses.
- No historical kit, perk, character interpretation, or visual law is automatically promoted.
- The complete referenced chat could not be retrieved because no callable thread reader was exposed. [D01](../sources/2026-09-25-author-handoff.md) is the direct author source for this pass.

The author reported making a separate backup. This migration neither depended on nor verified that external backup.

## Validation before publication

- All 68 archived working files matched their original Git blob identities with filters disabled.
- The staged archive subtree matched the original complete Git tree.
- All 17 recorded source and reading-copy SHA-256 checksums passed, resolving manifest paths within the archive.
- All 326 local Markdown link targets resolved across active and historical pages. External URLs were not exhaustively checked.
- The active-content change contained only 11 new files outside the archive; staged whitespace checks passed.
