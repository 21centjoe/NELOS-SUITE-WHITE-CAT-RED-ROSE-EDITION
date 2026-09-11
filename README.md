# NELOS-SUITE-WHITE-CAT-RED-ROSE-EDITION
Advanced Vault Suite with ENCRYPTION AND SELF-HEALING for your partitioned drive/USB

YES YOU CAN PURCHASE THIS TO MAKE YOUR OWN VERSION 
FOR licensing opportunities, please contact 21centjoe@gmail.com

# NELOS by Joseph La Follette

A geometric-computing file suite: real fullerene graphs (C60 outer shell, C20
inner core) used as the actual data structure for storage, redundancy, and
encryption — not decoration. Built with a strict rule: nothing in this UI
claims to do something it hasn't actually been tested to do.

## Running it
Open `index.html` in a Chromium-based browser (Chrome, Edge, or ChromeOS) for
full functionality — the USB/folder line prompt uses the File System Access
API, which is Chromium-only. Other browsers will run everything except that
piece.

## What's real in this build
- **Encryption**: AES-256-GCM via the browser's native Web Crypto API.
- **Compression**: real gzip via the native CompressionStream API.
- **Self-healing storage**: your file is split across a real, generated C60
  fullerene graph. Each of its 32 faces stores an XOR parity of its members,
  verified by CRC32.
- **Per-file Optimize**: encoding a file re-decodes and byte-for-byte verifies
  it before marking it "optimized" — nothing is marked done without an actual
  round-trip check passing.
- **PNG steganography**: vault data embedded in a genuinely valid PNG,
  confirmed openable in standard image viewers.
- **Universal preview**: images, audio, video, PDF, and plain text render
  directly. HTML files are shown as source only — never executed — since
  running untrusted HTML means running its scripts.
- **Genesis Tour**: a real, progressive walkthrough of the actual graph math.
- **Applets tab**: a real trigger-value lookup (store/retrieve, verified) and
  a real geometric calculator — hop distances via live BFS and redundancy
  overhead percentages, computed from the actual graph, not invented math.
- **Tutorial mode**: toggle in the header — shows a persistent plain-language
  label on every important control until you turn it back off.
- **Tab visibility toggles**: hide any of Explorer/Preview/Applets without
  losing what's loaded.
- **Honest limits, stated in the UI itself**: the parity system has a real
  recovery ceiling (bounded by 32 parity equations); ELA tamper detection is
  labeled as a heuristic, not a verdict; encryption protects data at rest,
  not on a compromised machine.


## License
Copyright (C) 2026 Joseph La Follette

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

