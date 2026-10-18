# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (`cfc019928`, extension **1.6.53**).

**joclio build:** **v1.6.55** (`versionCode` 106055). Same source as Keiyoushi 1.6.53, plus a workaround for [HTTP 503 / “Third-party apps are not supported”](https://github.com/keiyoushi/extensions-source/issues/20134): requests use a normal browser user agent, and a blocked page is reloaded in WebView without the app package header.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.min.json
```

Remove any old repo entry → force-close Tachimanga → reopen → add URL → **Browse → Extensions → refresh**.

### Manual install

https://github.com/joclio/extensions/releases/latest

Uninstall any older **Comix** first if the update does not replace it.

## Official Keiyoushi repo

If you only need stock Comix with no joclio patches:

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
