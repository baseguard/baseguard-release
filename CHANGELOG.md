# Changelog

## v0.2.8 (July 4, 2026)

### Fixes

- Windows: The MSI installer now bundles the WebView2 runtime, fixing the missing-runtime error on machines without it preinstalled.
- Auto-connect no longer keeps retrying when a node requires authentication; you'll be prompted to authenticate instead.
- Fixed an issue where a stale node connection status could permanently block reconnecting to a node.

## v0.2.1 (June 8, 2026)

### Features

* Auto-update: Baseguard keeps itself up to date automatically, or on demand with `baseguard update`.
