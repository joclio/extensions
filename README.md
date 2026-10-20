# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.126** (`versionCode` 106126). Same WebView/reader as 1.6.119. Fixes chapter refresh silently failing when the payload was too large for Tachimanga’s WebView bridge (slim chapters, drop unused `queries` blob), and still walks past the first known chapter so Webtoon can catch up.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.126**. Confirm Web View still works, then update **Reborn Rich** (Webtoon). Allow extra time on the update.

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
