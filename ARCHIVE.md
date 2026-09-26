# What Was Resonance: archive boundary and recovery

[Open the unchanged Resonance project](What%20Was%20Resonance/README.md).

The archive contains all **68 tracked files** present at the inspected pre-Duress commit, retaining their original relative structure, bytes, and Git file modes. No untracked or ignored project files were present in the inspected checkout. All prior Git history remains in the repository; Git's internal metadata remains at the repository root.

Historical documents are deliberately unchanged. Their “current,” “frozen,” and governing-source statements describe the preserved Resonance edition. Read them within that historical context, including its original editing instructions. The active Duress authority boundary is [here](canon/authority-and-status.md).

## Recovery points

- Inspected original commit: `03eed4a9dea9e2850163f7aa4e3952cf2d051684`.
- Preservation commit: `b16c7ef4dc3abe3d1a6f689c4f544c9c2517d692`.
- Annotated tag: `pre-duress-resonance-2026-09-25`.
- Archive-only commit: `7a2e1c0b666108196589ed287d96c82211d0490d`.

The preservation commit has the same tree as the original. The archive-only commit contains 68 exact moves with zero insertions or deletions. The archived subtree equals the original Git tree: `c1222617d7d136dd46491ed1be185810b1c641fe`.

For a separate copy of the pre-Duress project without changing the current checkout:

```sh
git archive --format=zip --output=pre-duress-resonance.zip pre-duress-resonance-2026-09-25
```

Original relative links remain relative to the archived project. Historical external links and root-relative path strings inside source records are retained as evidence, not rewritten. Interpret historical manifest paths from `What Was Resonance/`.

See the [migration audit](continuity/2026-09-25-migration.md).
