# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.110** (`versionCode` 106110). Restores the last working jar (**1.6.100**: chapter API find + bridge chunking for large lists). Rolls back the 1.6.101–1.6.109 chapter-list / site_api / header experiments that broke reading on Tachimanga.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.110**. Uninstall any older Comix first, including the Keiyoushi **1.6.54** row, so only one copy is loaded. The `index.min.json` address now downloads this same jar.

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
