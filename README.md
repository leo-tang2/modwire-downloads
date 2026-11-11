# Modwire 0.1.13 public test installers

Download without a GitHub or Vercel account: Windows x64 setup and Apple Silicon Mac DMG. The official page is https://modwire-gamma.vercel.app/downloads/ .

This update includes the approved circular app icon, inline password entry, native saved-session restoration and outage handling, eligible single-player library filtering, direct game-assistant navigation and bounded original mod creation. Support is specific to each adapter; a package build does not establish universal modding support.

Windows is unsigned. The Mac package is ad-hoc signed and NOT notarized: Gatekeeper assessment rejects this app and disk image on the tested Mac. The release app was not launched, to preserve the owner's profile. Apple Developer ID signing and notarization are still required for normal public distribution. No security bypass is included or recommended by this download. A separately built isolated debug app passed Mac navigation, library/empty-state, Settings, Account and masked signup/signin checks; that does not make this release-profile DMG notarized.

The complete source build f8f3753539030c78214ec8cbfe834af39e29a778 passed CI run 42956346574. Installer bytes/hashes and notices were checked. The candidate Mac package was checked on the connected macOS 26.7.2 ARM64 computer. No new AI generation, game modification or real payment was run for this publication.

Accounts use the existing Supabase integration and native OS credential store. The existing 25-credit grant and all prior balances are preserved. General verification email needs an owned sending domain; email confirmation stays enabled. Public shared Nexus service authorization is still pending. Credit purchases and auto refill remain gated off during testing; the new planned offer is $5 for 300 credits.

Source remains in the private owner repository. Required project and dependency notices are in the application; the complete incorporated Universal Modder MIT notice is retained. Older installers remain in repository history and their versioned filenames.
