# Comix extension (joclio)

Tracks **[Keiyoushi Comix](https://github.com/keiyoushi/extensions-source)** (published extension **1.6.54**).

**joclio build:** **v1.6.96** (`versionCode` 106096). Same bytecode as [Keiyoushi Comix 1.6.54](https://github.com/keiyoushi/extensions/releases/download/24bd7e6/tachiyomi-en.comix-v1.6.54.apk). Tachimanga rejects that APK’s OkHttp client method (`if-eqz` on an object), so those null checks were removed. The rest of the extension is unchanged.

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
