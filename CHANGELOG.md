# Changelog

This changelog records changes made for the maintained fork of `mack-a/v2ray-agent`.

## Scope

- Document fork-specific maintenance updates.
- Track installation and update entry point changes for this fork.
- Record compatibility, operational, and provenance updates.
- Keep upstream-origin changes visible and easy to review.

## Categories

- Documentation and provenance updates
- Install and update entry point changes
- Compatibility or maintenance fixes
- Operational improvements

## Entry Template

```text
## YYYY-MM-DD

- Summary: ...
- Type: documentation | maintenance | compatibility | operational
- Impact: ...
- Notes: ...
```

## Upstream Sync Note

When upstream changes are imported from `mack-a/v2ray-agent`, summarize the fork-visible impact here and keep the full sync process documented in `UPSTREAM-SYNC.md`.

## 2026-09-25

- Summary: Validate custom UUID and personalized-install inputs; pin VLESS+Reality+XHTTP+TLS to port 443
- Type: compatibility
- Impact: Invalid UUIDs and malformed option/port inputs no longer produce broken configs; option-12 XHTTP deployments always use 443 instead of a prompt-driven port
- Notes: Fork-specific hardening committed before syncing upstream master
