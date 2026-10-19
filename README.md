# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (`cfc019928`, extension **1.6.53**).

**joclio build:** **v1.6.82** (`versionCode` 106082). Same source as Keiyoushi 1.6.53, plus a workaround for [HTTP 503 / “Third-party apps are not supported”](https://github.com/keiyoushi/extensions-source/issues/20134). Every Comix method that mixed a number and an object in one register was simplified so Tachimanga can verify the class. Search, chapter ids, and page lists are empty or defaulted in this build.

## Install on Tachimanga (iPad/iPhone)

### Extension repository (recommended)

```
https://raw.githubusercontent.com/joclio/extensions/main/index.min.json
```

Needs Tachimanga **4.16 or newer** (extension library 1.6). Remove the repo entry → force-close Tachimanga → reopen → add the URL again → **Browse → Extensions → refresh**. Turn on NSFW sources if Comix is still hidden.

### Manual install

https://github.com/joclio/extensions/releases/latest

Uninstall any older **Comix** first if the update does not replace it.

## Official Keiyoushi repo

If you only need stock Comix with no joclio patches:

```
https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json
```

Use **one** repo at a time to avoid version confusion.
