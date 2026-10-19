# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.111** (`versionCode` 106111). Keeps the working reader/WebView from **1.6.110**, and fixes chapter refresh by calling Comix’s hidden GET client directly (the old chapter-method + tap path no longer exists on the live site).

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.111**. Uninstall any older Comix first, including the Keiyoushi **1.6.54** row, so only one copy is loaded. The `index.min.json` address now downloads this same jar.

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
