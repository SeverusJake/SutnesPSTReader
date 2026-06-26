# Sutnes PST Reader

A fast, self-contained **Windows** desktop app to **read and search Outlook PST / OST**
mailbox files — **no Outlook, no MAPI, no install** required.

## Download

**→ [Latest release](https://github.com/SeverusJake/SutnesPSTReader/releases/latest)**

- `SutnesPSTReader-v<version>-installer.exe` — Windows installer (Start Menu + Desktop
  shortcuts, uninstaller).
- `SutnesPSTReader-v<version>-portable.exe` — single self-contained `.exe`, just run it.

Windows 10/11 (x64). The **Microsoft Edge WebView2 Runtime** is required to render email
bodies (preinstalled on Windows 11; free download from Microsoft on Windows 10).

## Features

- Reads **PST and OST** without Outlook; **fast open** even on tens-of-GB files (lazy reader).
- Full-text search (subject + body), inline search operators, sort/group.
- **Multiple mailboxes** at once; persistent read/flag.
- **Export** a folder or a whole mailbox to **`.pst`** or **`.mbox`** (with subfolder/`.sbd`
  structure); save/drag messages as **`.eml`** / **`.msg`**.

## License & third-party notices

This repository distributes **release binaries only**; the application itself is
proprietary (closed source).

The binary includes the **PSTFileFormat** library (© 2012-2016 ROM Knowledgeware,
Tal Aloni), used to read and write `.pst` files, licensed under the **GNU LGPL-3.0-or-later**:

- PSTFileFormat source code: <https://github.com/ROM-Knowledgeware/PSTFileFormat>
- License texts: [`licenses/LGPL-3.0.txt`](licenses/LGPL-3.0.txt),
  [`licenses/GPL-3.0.txt`](licenses/GPL-3.0.txt)
- All third-party components and licenses: [`THIRD-PARTY-NOTICES.txt`](THIRD-PARTY-NOTICES.txt)

In accordance with the LGPL, the corresponding source of that component is available at the
link above; contact the author to obtain the object code required to relink the application
against a modified version of the library.

> Not affiliated with Microsoft. "Microsoft", "Outlook", and the `.pst` format are
> trademarks/products of Microsoft Corporation.
