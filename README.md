# Sn compiler downloads and issues

Official binary releases and public issue tracking for the **Sn programming language**,
a Logic & Lore Interactive product.

Sn is a proprietary systems language under heavy development. The compiler
implementation and its private development history are not published here.
The standard-library Sn sources are intentionally included with compiler downloads.

- [Download Sn 0.2.0 Preview 1 for Linux x86_64](https://github.com/RichmarIII/sn-releases/releases/tag/v0.2.0-preview.1)
- [Matching installation guide](https://sn.logicnlore.com/docs/0.2.0-preview.1/getting-started/)
- [Matching standard-library reference](https://sn.logicnlore.com/reference/0.2.0-preview.1/)
- [Report a bug](https://github.com/RichmarIII/sn-releases/issues/new/choose)
- [Language website](https://sn.logicnlore.com/)

The Linux package requires glibc 2.35 or newer. LLVM and non-glibc runtime
dependencies are bundled. AOT builds also require the system Clang C driver and development headers; the matching linker is bundled.
Read the release's README and VALIDATION files for tested workflows and known
limitations, including the automatic C-import preparation failure in this preview.
The intended 1.0 goals on the website are not a guarantee about this development release.

Download the compiler **release asset**, not GitHub's automatically generated
“Source code” archives. Those archives contain only this distribution repository's
README and issue configuration; they do not contain the compiler implementation.

When reporting a bug, include the release version, platform, exact command, a
small reproducing example, and actual output. Share only material you intend to
make public; remove credentials and private project content.
