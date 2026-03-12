## Fixed
- Fixed Add Account failures caused by GUI launch environments that could find `codex` but not its `node` runtime
- Improved OAuth diagnostics so app-server exit status and stderr are shown instead of a generic close message
- Improved auth-file recovery after login completion in temporary `CODEX_HOME` environments

## Notes
- This release fixes the `status 127` Add Account failure
- Existing Codex desktop sessions still require restart after switching accounts
- Existing CLI sessions still require opening a new session after switching accounts
