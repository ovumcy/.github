# Ovumcy

**Privacy-first, self-hosted menstrual cycle tracking — your health data stays under your control.**

Ovumcy is an open-source ecosystem for tracking periods, predicting cycles, and owning
your data. No cloud account required, no analytics, no ad trackers. Self-host the server,
run the mobile app locally, or combine both with your own encrypted sync.

Project site: [ovumcy.com](https://ovumcy.com)

## Pick your component

| Repository | What it is | Choose it when |
| --- | --- | --- |
| [ovumcy-web](https://github.com/ovumcy/ovumcy-web) | Self-hosted all-in-one web app and server (Go) | You want one self-hosted server with a browser UI |
| [ovumcy-app](https://github.com/ovumcy/ovumcy-app) | Local-first mobile client for iOS and Android | You want an on-device, local-first mobile experience |
| [ovumcy-sync-community](https://github.com/ovumcy/ovumcy-sync-community) | Self-hosted zero-knowledge sync backend | The mobile app needs encrypted backup, restore, or multi-device sync |

`ovumcy-web` is a complete product on its own. `ovumcy-app` works fully offline; add
`ovumcy-sync-community` only when you want self-hosted encrypted sync across devices.

## What makes Ovumcy different

- **Self-hosted or on-device.** Data lives on infrastructure you control, never a vendor cloud.
- **No telemetry.** No analytics or ad trackers by product default; no outbound calls in the default configuration.
- **Zero-knowledge sync.** The optional sync backend stores encrypted blobs and metadata, never plaintext health data.
- **Open and portable.** CSV/JSON export, a documented API, AGPL v3.

## Not a medical device

Ovumcy provides estimates and logs based on the data you record. Predictions are
statistical estimates — not a contraceptive method, fertility treatment, or a substitute
for medical care.

## Contributing & security

Planning lives in GitHub Issues. Found a security issue? Please report it privately
(`contact@ovumcy.com`) rather than opening a public issue — see each repository's `SECURITY.md`.

Licensed under AGPL v3.
