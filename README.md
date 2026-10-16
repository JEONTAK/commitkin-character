# Commitkin author installation

User-owned configuration for [Commitkin](https://github.com/JEONTAK/commitkin), separated from the product repository so future forks inherit no personal character history.

This is the explicitly reviewed ordinary-repository author installation: `JEONTAK/commitkin-character`, repository ID `1421634321`, owner account ID `76037656`. Other users install in actual public personal forks of the product repository. Renaming, transferring or recreating this repository requires a separate identity review.

## First snapshot saved

JEONTAK explicitly confirmed permanent **Bloomguard** selection before storage on 2026-10-16. The [one-time initialization](https://github.com/JEONTAK/commitkin-character/actions/runs/38854047488) succeeded with the basic repository token: **Lv.1 Adventurer, 20 XP**, 22 known public repositories and 607 total runtime requests (594 read-side requests plus 13 publication requests).

The [first saved commit](https://github.com/JEONTAK/commitkin-character/commit/d89ede9193f85b77e8bb847a6157de805c9edd04) contains exactly three matching growth records, `character.png` and display-only `profile.json` under `.commitkin/`, preserving all unrelated files. Record schema/owner/cross-file checks, display fields and the actual PNG digest/pixels were verified. Revision 2 is the first persisted ready snapshot: revision 1 was an in-memory initial pending candidate, not an earlier live write or duplicate reward.

## Current mode: manual, read-only preview

The temporary job-local write permission has been removed. **Commitkin author preview** is manual-only, `contents: read`, pinned to a reviewed full source SHA and literal `dry-run: 'true'`. It supplies no new faction or initialization confirmation, preserves the saved Bloomguard choice and does not publish further growth. There is no schedule, push hook, automatic sync or PAT.

Optional public analysis settings are in [`.github/commitkin.yml`](.github/commitkin.yml). Automatic discovery, additional repositories and exclusions follow the existing product rules. Empty lists do not narrow analysis or silently drop unavailable known repositories.

The separate manual profile-sync workflow in [JEONTAK/JEONTAK](https://github.com/JEONTAK/JEONTAK/actions/workflows/commitkin-profile-sync.yml) reads the saved display snapshot from here and validates its fixed-head model/PNG. Dry-run prepares native Markdown in memory; separately authorized publication may update only the profile's managed README block. On 2026-10-16, JEONTAK explicitly authorized one such manual display publication without changing these five growth/display files. The profile workflow returns to read-only dry-run afterwards; no automatic execution is enabled.

Further growth refreshes remain unauthorized. Display publication uses only the profile repository's own basic token and never recomputes or rewrites this installation's growth. Only this repository stores settings and the matched growth/display bundle; the profile receives native Markdown around a character-only image link. Retain valid same-owner/storage history for recovery; never reset or rebind records to change faction.
