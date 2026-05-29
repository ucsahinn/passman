# PassMan Knowledge Base

Redaction-first operational troubleshooting for PassMan Enterprise Vault Console.

Use these entries when diagnosing public-safe symptoms. Never paste secrets, real tokens, databases, private keys, certificate packages or screenshots containing secret records into public support channels.

## Fast Paths

| Incident Path | English | Turkish |
| --- | --- | --- |
| MSI installation fails | [EN](en/msi-installation-fails.md) | [TR](tr/msi-installation-fails.md) |
| Update stays around 76 percent | [EN](en/update-stuck-76.md) | [TR](tr/update-stuck-76.md) |
| DC Agent service cannot connect | [EN](en/dc-agent-service.md) | [TR](tr/dc-agent-service.md) |
| Extension pairing remains pending | [EN](en/extension-pairing.md) | [TR](tr/extension-pairing.md) |
| Certificate warning | [EN](en/certificate-warning.md) | [TR](tr/certificate-warning.md) |
| Audit chain is partial | [EN](en/audit-chain-partial.md) | [TR](tr/audit-chain-partial.md) |
| License is read-only | [EN](en/license-read-only.md) | [TR](tr/license-read-only.md) |
| External share package fails | [EN](en/external-share-fails.md) | [TR](tr/external-share-fails.md) |

## What To Collect

- PassMan version and component version.
- Windows Server version.
- MSI filename and signature status.
- Configured host and port.
- License state and active user count.
- Redacted timestamps and log excerpts.
- Whether the issue affects login, vault records, sharing, extension, AD sync, backup, update or installer flow.

## Do Not Share

- Master passwords, secret values or share passphrases.
- AD bind passwords, agent tokens or license private keys.
- Database files, backups, PFX/P12 files or private keys.
- Screenshots that reveal secret records, users, internal URLs or customer data.

Related surfaces:

- [Repository home](../README.md)
- [Documentation](../docs/README.md)
- [Security policy](../SECURITY.md)
- [Support policy](../SUPPORT.md)
