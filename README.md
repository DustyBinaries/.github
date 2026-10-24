# DustyBinaries

**Old compilers. Real software.**

DustyBinaries was born from a simple motivation: to show that old technologies such as
**Delphi 7**, **Pelles C** and the **Digital Mars** compilers can still build useful, and even
beautiful, software.

These tools are small, fast and self-contained. They produce native binaries with no runtime to install
and no gigabytes of toolchain. Nothing about them stops you from writing modern, polished software.
What they lack is attention, and the projects below try to give them some.

## Projects

| Project | What it is |
|---|---|
| [Borion](https://github.com/DustyBinaries/Borion) | A "Tauri-style" native application engine for Delphi 7: HTML/CSS/JS interfaces on WebView2, native logic in Delphi, and an `invoke` / `emit` / `listen` bridge between them. |
| [WebView2](https://github.com/DustyBinaries/WebView2) | The `TWebView2Browser` control for Delphi 7, the foundation of Borion. It can also be used on its own in a regular Delphi 7 app. |
| [fbstats](https://github.com/DustyBinaries/fbstats) | A Firebird size statistics tool (Delphi 7 + Borion): page census, BLOB measurement and duplication analysis behind a web interface. |
| [fsql](https://github.com/DustyBinaries/fsql) | A Firebird command-line shell modelled on the `sqlite3` CLI, written in Delphi 7 on Zeos. It replaces `isql` for day-to-day work. |
| tdb | A gdb/pdb-style command-line debugger for Delphi 7 programs. It hosts Borland's own debug kernel (`BORdbk70.dll`) through COM. |
| [UReadLine](https://github.com/DustyBinaries/UReadLine) | A minimal GNU-readline-like line editor for the Windows console, written in Delphi 7 with no dependencies beyond the RTL and the Windows API. |

## Principles

- **Old toolchains, current results.** Every project is built with a vintage compiler.
- **Native and lightweight.** Small executables, no heavy runtimes, quick startup.
- **Useful first, nostalgic second.** The tools solve real problems today.
- **Modern where it counts.** Web UIs on WebView2, CLI ergonomics from sqlite3 and readline, and debugging in the style of gdb.

## Contributing

Issues and pull requests are welcome in each project's repository.
