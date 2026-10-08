# Watta Switch — your coding tools, your choice of model

[![Latest release](https://img.shields.io/github/v/release/srknlabs/watta_ai_switch?display_name=tag&sort=semver)](https://github.com/srknlabs/watta_ai_switch/releases/latest)

Keep working in **Codex and Claude Code**. Connect them to [Watta](https://watta.io), choose compatible models from your account, and manage access and usage from one desktop app.

Watta Switch gives each App and CLI its own switch and model selection. Enable the integrations you need, try another model, and restore the original configuration when you are done.

**[Install for macOS →](https://watta.io/apps/watta-switch)** · [Create a Watta account](https://watta.io/register) · [Plans and Energy](https://watta.io/pricing) · [Support](https://watta.io/contact)

## Install on your Mac

For **Apple Silicon** Macs, run in Terminal:

```sh
curl -fsSL https://watta.io/apps/watta-switch/install.sh | sh
```

The installer downloads the app, verifies its SHA-256 checksum and code signature, and installs it in `/Applications` when that folder is writable. It does not use `sudo`. Sign in to Watta, select your models, and enable Codex or Claude Code. Restart the connected app when prompted.

| Platform | Availability |
| --- | --- |
| macOS Apple Silicon | Terminal installer and [DMG](https://github.com/srknlabs/watta_ai_switch/releases/latest) |
| macOS Intel | [DMG](https://github.com/srknlabs/watta_ai_switch/releases/latest) |
| Linux | Coming soon |
| Windows | Coming soon |

Codex and Claude Code must be installed separately. Model access depends on compatibility, your plan, Energy, credits, and current availability.

## What you can do

- **Keep your workflow.** Use your existing coding tools with Watta's compatible model catalog.
- **Choose independently.** Configure Codex App, Codex CLI, Claude Code App, and Claude Code CLI separately.
- **See model access before selecting.** Provider groups, search, Energy estimates, and plan or credit requirements make the catalog easier to navigate.
- **Try temporary-access models.** Eligible models are marked **Temp access**. Promotional access rotates and expires; check the current catalog and account limits before using it.
- **Return to your original setup.** Switch an integration off to restore its previous configuration. Watta-owned settings are tracked separately from unrelated edits.
- **Follow usage.** View request activity and open your Watta usage dashboard from the sidebar.
- **Stay close to your tools.** A macOS menu-bar app with light, dark, and system themes, account details, and update checks.

## One account for model access

Sign in through your browser with Watta OAuth. You do not need to paste separate provider API keys into the app. Choose Watta Free, Lite, Pro, Max, or another compatible model available to your account. The catalog reflects current availability and pricing.

Promotional models have temporary access, rather than permanent inclusion in a plan. Paid usage follows your account's Energy and wallet-credit rules. See [Plans and Energy](https://watta.io/pricing) and [Usage](https://watta.io/dashboard/usage).


## Privacy and security

Sign-in uses Watta OAuth with PKCE. Access and refresh tokens are stored in macOS Keychain. Local configuration snapshots are encrypted. Prompts and the context required by your coding tool are routed through Watta to generate responses; see the [Privacy Policy](https://watta.io/privacy) and [Terms](https://watta.io/terms).

The current macOS release uses an ad-hoc signature and is not notarized by Apple. macOS can ask for permission to open the app or access Keychain, including after an update changes its signing identity.

## Updates and support

Use **Check update** in the app to check the published version. Automatic installation requires signed updater artifacts; install the current release through Terminal or [GitHub Releases](https://github.com/srknlabs/watta_ai_switch/releases/latest).

Need help or have feedback? Visit [Watta support](https://watta.io/contact) or open an [issue](https://github.com/srknlabs/watta_ai_switch/issues). Please report security vulnerabilities privately and remove tokens and personal data from logs.

## About this repository

This repository is the public product page and download channel for Watta Switch. It contains product documentation and ready-to-install releases. Application source code, backend code, internal configuration, and source history are not published here.

Codex and Claude Code are products of their respective owners. Watta Switch is an independent integration.

