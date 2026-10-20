# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.118** (`versionCode` 106118). After checking the real app path: OkHttp HTML has no chapter rows, so WebView must let the site paint them, then we scrape. Wait raised to 90s; stale-date skip disabled; still no extension API calls.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.pb
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Install **Comix English 1.6.118**. Web View must show the normal Comix site (not third-party). Then update a series.

### Manual install

https://github.com/joclio/extensions/releases/latest

## Official Keiyoushi repo

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
