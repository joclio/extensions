# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.113** (`versionCode` 106113). Restores the working **1.6.110** reader/`site_api` (1.6.112 broke those). Keeps only the fast GET-based chapter refresh on top.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.113**. Uninstall any older Comix first, including the Keiyoushi **1.6.54** row, so only one copy is loaded. The `index.min.json` address now downloads this same jar.

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
