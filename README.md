# hacs-ha_health_record — retired

This repository is **archived**. It mirrored a single integration out of
[WOOWTECH/Woow_ha_records](https://github.com/WOOWTECH/Woow_ha_records) because
HACS installs one integration per repository.

Since version 2.0.0 the four integrations are one — `woow_ha_records` — so the
source repository is itself the HACS repository and this mirror has nothing left
to mirror.

## Install the replacement

HACS → ⋮ → Custom repositories → add
`https://github.com/WOOWTECH/Woow_ha_records` (type: Integration) → Download →
restart Home Assistant.

2.0.0 is a clean break with no migration: remove the old integration, delete its
`custom_components/` directory, install the new one, and re-enter your data.
Entity IDs, service names and WebSocket commands all changed. See
[ADR-0001](https://github.com/WOOWTECH/Woow_ha_records/blob/main/docs/adr/0001-merge-four-integrations-into-one-domain.md).
