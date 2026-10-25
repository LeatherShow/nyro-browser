# Nyro Browser

A Windows Chromium/Brave fork with a customizable start page, local widgets, fingerprinting controls, and a choice of built-in blocking or bundled uBlock Origin.

Created by **FoidKiller3000** · [@foidki](https://www.tiktok.com/@foidki)

## Testing preview

This project is under development. Version 1.99.31 preview 1 is an unsigned Windows x64 testing build. Automatic browser updates are disabled. This is not a stable maintained browser.

[Downloads, matching source snapshot and validation notes](https://github.com/LeatherShow/nyro-browser/releases)

The installer is 258,885,632 bytes (259 MB / 247 MiB). Build objects and debug symbols are excluded. No memory or speed advantage over other production browsers has been established.

## Matching source

The source snapshot attached to the release contains pinned Chromium and Brave patches, added source files, reconstruction instructions, build arguments, component sources and license notices. This repository is the distribution index; it does not duplicate the entire upstream checkout. Use the matching source snapshot release asset rather than GitHub's automatically generated archive of this index repository.

Upstream bases:

- Brave Core: `094740069b0ed6e75011e98044f226ff34ade72e`

- Chromium: `1228231501697ff7a4a0150ea8ae6df37bb99331`

Preserve upstream copyrights and licenses. Chromium, Brave, extensions and blocking components have their own licenses; see the source snapshot for the actual texts and corresponding sources.

## Verification and limits

The optimized build, 34 new-tab tests, runtime smoke tests and extension integration tests pass. The latter two suites also pass against the extracted installer payload. Font, screen and language fingerprinting probes demonstrate the tested default settings, global toggle and site exceptions.

Windows setup, registry/shortcuts, upgrade/uninstall and elevation still need testing in a disposable VM. Full site compatibility and every privacy pathway are not verified. Public IP and timezone remain visible, and network requests still occur. No VPN, Tor-level anonymity or Firefox add-on compatibility is provided.

Consult the release's `VALIDATION.md` for test scope, limitations and checksums. Report reproducible problems through [Issues](https://github.com/LeatherShow/nyro-browser/issues).



