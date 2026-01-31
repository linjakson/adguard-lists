# adguard-lists

Custom AdGuard Home filter list for client-specific blocking rules.

## What this repository does

- Maintains `agh-custom.txt`, a list of AdGuard filter rules.
- Targets specific devices via `$client=IP` to apply different blocking scopes.
- Focuses on blocking selected domains (including many mainland China sites) for chosen clients.

## Files

- `agh-custom.txt` — the active filter list used by AdGuard Home.

## How to use

1. Add the raw list URL to AdGuard Home:
   - `https://raw.githubusercontent.com/linjakson/adguard-lists/main/agh-custom.txt`
2. Reload filters and confirm rules are taking effect in the query log.

## Contributing

- Follow `AGENTS.md` for repository guidelines.
- Keep rules grouped and one per line.
- Validate changes in AdGuard Home before pushing.
