# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.122** (`versionCode` 106122). Fixes Reborn Rich–style gaps: page-1 is only the highest chapter numbers (HiveToons/QI), so Webtoon 204 never appeared. Now pages forward until a known chapter is found, and stops skipping refreshes after an old “complete” fetch.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.122**. Confirm Web View still works, then update **Reborn Rich** (expect Webtoon chapters past 195, and/or newer chapters from other groups).

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
