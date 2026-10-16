# Commitkin author installation

User-owned configuration for [Commitkin](https://github.com/JEONTAK/commitkin), separated from the product repository so future forks inherit no personal character history.

This is the explicitly reviewed ordinary-repository author installation: `JEONTAK/commitkin-character`, repository ID `1421634321`, owner account ID `76037656`. Other users install in actual public personal forks of the product repository. Renaming, transferring or recreating this repository requires a separate identity review.

## One-time initialization authorized

JEONTAK explicitly confirmed permanent **Bloomguard** selection on 2026-10-16. The existing manual preview workflow is temporarily pinned to that first choice with job-local `contents: write` and explicit publication. The reviewed runtime requires verified empty record history and rejects these first-choice inputs after records exist. No profile publication or automatic execution is enabled. After this one manual initialization, the workflow will return to read-only dry-run without faction/confirmation inputs. The statements below describe its previous preview-only mode; no successful saved snapshot is claimed until verified from the publication commit.

## Previous mode: manual, read-only preview

Run **Commitkin author preview** manually in Actions. The temporary preview faction is used in memory only. The workflow uses this repository's basic `GITHUB_TOKEN`, `contents: read`, a reviewed full source SHA and literal `dry-run: 'true'`. No permanent faction, growth record, display projection or PNG is saved. There is no schedule, push hook, automatic sync or PAT.

Optional public analysis settings are in [`.github/commitkin.yml`](.github/commitkin.yml). Automatic discovery, additional repositories and exclusions follow the existing product rules. Empty lists do not narrow analysis or silently drop unavailable known repositories.

The separate manual profile-sync preview in [JEONTAK/JEONTAK](https://github.com/JEONTAK/JEONTAK/actions/workflows/commitkin-profile-sync.yml) reads a previously published display snapshot from here. There is deliberately no saved snapshot yet: sync must safely hold and preserve the profile, not fabricate data or write records to make the preview pass.

Real growth publication and profile publication require separate approval. If enabled later, only this repository stores settings and the matched five-file growth/display bundle; the profile receives native Markdown around a character-only image link. Keep valid same-owner/storage history for recovery; never reset or rebind records to change faction.
