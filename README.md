# Modwire public test installers

Windows: 0.1.15. Mac: 0.1.14 (0.1.15 pending).

Download without a GitHub or Vercel login at https://modwire-gamma.vercel.app/downloads/ .

Modwire 0.1.15 for Windows preserves conversations through connection interruptions, refreshes expired project checks automatically, repairs Epic detection and adds persistent Choose game folder support without launcher registration. No AI is used to find games.

All application test steps and both native build steps passed in CI. The workflow then failed or stalled transferring artifacts. The Windows installer published here was rebuilt locally from the identical tested source and audited for architecture, public configuration, icons, notices and private material. The development app started, but visual button checks were blocked by desktop-control errors. Epic detection was tested with fixtures because this computer has no Epic installation records. No AI, gameplay, email or payment test was made; spending was $0.

The Mac download remains 0.1.14. Its 0.1.15 update is blocked by GitHub package transfer/run-state failures; an alternate export is queued and unpublished. No connected-Mac runtime test was performed. Windows is unsigned; the existing Mac package is ad-hoc signed and not notarized. Publishing does not update the installed app. Conversation continuation retains the current running window, not a full process-restart transcript. Existing balances, spending caps, eligibility checks and creation workflows are preserved. Public arbitrary-inbox verification email still needs a verified sending domain/SMTP.

Native Windows build source: 6b230532c1888218f46a76f55fc99b0d14b12586. Original CI: https://github.com/leo-tang2/modwire/actions/runs/43094730341.

Source remains private. Required notices are included. Older installers are preserved.
