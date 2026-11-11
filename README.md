# Modwire 0.1.14 public test installers

Download Windows x64 or Apple Silicon Mac without a GitHub or Vercel login at https://modwire-gamma.vercel.app/downloads/ .

This update adds the rotating Modwire startup logo, bounded local startup checks, deferred game discovery, automatic saved-session restore and refresh, and recovery from temporary account-service failures. The server fix is deployed. Existing single-player checks, supported Universal Modder workflows, account identities and balances are preserved.

Windows is unsigned. The Mac build is ad-hoc signed in CI and NOT notarized; macOS may block normal downloaded-app launch. This 0.1.14 package has not been launched on the connected Mac: the owner deferred that computer's testing. Windows visual/button checks were blocked by the desktop lock. Automated native, frontend and backend tests and package/configuration/icon/license checks passed for exact source 2ded7d0c771935cfb689b8c9f364872397fc686b, CI run 43051979018. Earlier isolated Windows development startup, real verified-account restore/refresh and sign-out checks passed. No new AI, payment or gameplay test was performed.

Public arbitrary-inbox verification email still requires a verified sender domain and custom SMTP; email confirmation remains required. Public shared Nexus application authorization and sales readiness gates remain unchanged. No additional grant or spending was created for this release.

Private source remains in the owner's source repository. Required notices are included in the applications; older installers remain available by versioned filename/history.

CI limitation: the Linux job was canceled after Ubuntu DNS failures on two runners, before application tests began. The aggregate CI run is not green. Windows/Mac build jobs passed; the frontend, backend, startup, account and workflow checks passed locally. No Linux installer is published.
