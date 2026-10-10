# woia-asset-management

Coordinate accepted asset administration, obligations, incidents, changes and residual work without financial or legal takeover.


See [skill](skills/woia-asset-management/SKILL.md), [method contract](skills/woia-asset-management/references/CONTRACT.md).

Core owns work mechanics. Shared providers own their business facts and effects. Outcome requirements come from an accepted, immutable typed contract resolved by the host. Physical provider/runtime qualification and Operator E2E are NOT_RUN; Production Ready is false.

## Maintenance

Edit only this canonical repository. Keep `plugin.json`, `package.json` and `dev.woia/manifest.json` versions aligned. From the canonical WOIA Ecosystem repository, run `mise run plugin:certify-thin --repo <absolute-plugin-repository>`, then use its release preparation/publication tasks. Install and update consumers from immutable published artifacts; keep Project personalization in overlays.
