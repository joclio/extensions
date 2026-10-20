# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.123** (`versionCode` 106123). Same WebView/reader as 1.6.119. Disables the stale “chapters unchanged” skip that blocked refreshes (Reborn Rich stuck at 195). Reverts the 1.6.122 chapter_list rewrite that caused NullPointerException.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.123**. Confirm Web View still works, then update **Reborn Rich**.

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
