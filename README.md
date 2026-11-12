# Modwire public test installers

Modwire 0.1.15 — Windows and Apple Silicon public test installers

Download without a GitHub or Vercel login: https://modwire-gamma.vercel.app/downloads/

The Mac installer now includes 0.1.15's persistent Choose game folder, free local game finder, repaired Epic discovery and conversation recovery. It was built from the exact private source below and tested on the connected Apple Silicon Mac. Native folder selection/cancel, duplicate selection, restart/rescan persistence, unsupported-folder blocking and both Mac Epic scan roots passed. Epic fixtures covered namespace:item identity, duplicate records, malformed/relative paths, incomplete installations and the launcher-index fallback. These are controlled discovery tests; no real-game compatibility or gameplay result is claimed.

Mac checks: 46 frontend tests, 151 backend tests and 212 native tests passed; 20 opt-in native tests remained ignored. The frontend build, backend typecheck and native packaging passed. The actual /Applications/Modwire.app was updated from 0.1.1 to 0.1.15, with a private backup and the original profile preserved. Packaged, built and installed app files match. Independent payload checks verified ARM64, public service routing, icon and required notices, with no known private credentials present. No AI, payment, email or gameplay test was made; additional AI spending was $0.

Apple security is NOT resolved: the owner has no Apple Developer Program membership. This Mac build is ad-hoc signed and NOT notarized; Gatekeeper rejects its distribution assessment and may block normal downloaded-app launch. Do not interpret successful local development launch as notarization or a verified browser-download first launch. Developer ID signing and Apple notarization are still required. Windows remains the previously published unsigned test installer, byte-for-byte unchanged.

Mac build source: 5c99e505ace4a32a9f8c2be21fedb0cbb549497c
Native implementation: 6b230532c1888218f46a76f55fc99b0d14b12586
Mac: Modwire_0.1.15_aarch64.dmg, 6505704 bytes
Mac SHA-256: 6523c9cbaa3007f2c5ce34479542a85fc70980c8deb935dd0e8b5242a2cee5ec
Windows SHA-256: 31d51174c8fb8620c7999b897a1bdada4f7da3c9d5809e4091e004e320a3f059

Source remains private. Required third-party notices are included, older installers are preserved, and no automatic updater is enabled. Public arbitrary-inbox verification email still requires the existing sending-domain/SMTP prerequisite. Conversation recovery does not claim full process-restart transcript persistence.
