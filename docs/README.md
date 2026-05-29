# PassMan Documentation Gateway

This folder is the public-safe operator wiki for PassMan Enterprise Vault Console. Choose a language home first, then follow the lifecycle path that matches the job.

| Language | Home | Best for |
| --- | --- | --- |
| English | [English documentation home](en/README.md) | Installation, operation and support teams working in English. |
| Turkish | [Türkçe doküman ana sayfa](tr/README.md) | Türkçe kurulum, operasyon ve destek akışları. |

## Operator Lifecycle

| Stage | English | Turkish |
| --- | --- | --- |
| Understand | [Overview](en/overview.md), [FAQ](en/faq.md) | [Genel bakış](tr/overview.md), [SSS](tr/faq.md) |
| Install | [Windows Server installation](en/install-windows-server.md), [First run, owner and license](en/first-run-owner-license.md) | [Windows Server kurulumu](tr/install-windows-server.md), [İlk kurulum, owner ve lisans](tr/first-run-owner-license.md) |
| Publish | [Public host and HTTPS](en/public-host-https-certificate.md), [Browser extension](en/browser-extension.md) | [Public host ve HTTPS](tr/public-host-https-certificate.md), [Tarayıcı eklentisi](tr/browser-extension.md) |
| Secure | [Audit and security posture](en/audit-and-security-posture.md), [Active Directory agent](en/active-directory-agent.md) | [Denetim ve güvenlik duruşu](tr/audit-and-security-posture.md), [Active Directory ajanı](tr/active-directory-agent.md) |
| Operate | [Sharing and offline decrypter](en/sharing-and-offline-decrypter.md), [Backups and restore](en/backups-and-restore.md), [Update Center](en/update-center.md) | [Paylaşım ve offline decrypter](tr/sharing-and-offline-decrypter.md), [Yedekleme ve geri yükleme](tr/backups-and-restore.md), [Güncelleme Merkezi](tr/update-center.md) |
| Diagnose | [Troubleshooting](en/troubleshooting.md), [Knowledge base](../kb/en/README.md), [Support policy](../SUPPORT.md) | [Sorun giderme](tr/troubleshooting.md), [Bilgi bankası](../kb/tr/README.md), [Destek politikası](../SUPPORT.md) |

## Guide Map

| Guide | English | Turkish | Purpose |
| --- | --- | --- | --- |
| Overview | [EN](en/overview.md) | [TR](tr/overview.md) | Product model, runtime boundaries and recommended path. |
| Windows Server installation | [EN](en/install-windows-server.md) | [TR](tr/install-windows-server.md) | MSI install, service state, port, logs and validation. |
| First run, owner and license | [EN](en/first-run-owner-license.md) | [TR](tr/first-run-owner-license.md) | Owner profile, license activation and first-run checks. |
| Public host and HTTPS | [EN](en/public-host-https-certificate.md) | [TR](tr/public-host-https-certificate.md) | Hostname, certificate package upload and browser validation. |
| Update Center | [EN](en/update-center.md) | [TR](tr/update-center.md) | Signed manifest, MSI updates and component release notes. |
| Browser extension | [EN](en/browser-extension.md) | [TR](tr/browser-extension.md) | Pairing, badge counts, autofill and save/update prompts. |
| Active Directory agent | [EN](en/active-directory-agent.md) | [TR](tr/active-directory-agent.md) | PassMan DC Agent Service install, repair, logs and sync tree. |
| Sharing and offline decrypter | [EN](en/sharing-and-offline-decrypter.md) | [TR](tr/sharing-and-offline-decrypter.md) | Internal sharing, external packages, files, expiry and usage limits. |
| Backups and restore | [EN](en/backups-and-restore.md) | [TR](tr/backups-and-restore.md) | Encrypted backup export, integrity and restore checks. |
| Audit and security posture | [EN](en/audit-and-security-posture.md) | [TR](tr/audit-and-security-posture.md) | Audit chain, posture score and risk actions. |
| Troubleshooting | [EN](en/troubleshooting.md) | [TR](tr/troubleshooting.md) | Common operational failure states. |
| FAQ | [EN](en/faq.md) | [TR](tr/faq.md) | Short answers for operators and administrators. |

## Visual References

| Surface | Asset |
| --- | --- |
| Security dashboard | [overview-security-posture.png](../assets/screenshots/overview-security-posture.png) |
| Secret records | [passwords-record-list.png](../assets/screenshots/passwords-record-list.png) |
| Sharing lifecycle | [sharing-package-flow.png](../assets/screenshots/sharing-package-flow.png) |
| AD sync tree | [active-directory-sync-tree.png](../assets/screenshots/active-directory-sync-tree.png) |
| Offline decrypter | [offline-share-decrypter.png](../assets/screenshots/offline-share-decrypter.png) |

## Documentation Rules

- Keep Turkish and English document sets paired.
- Use placeholders for hosts, users, tokens and license values.
- Do not include private source code, signing material, customer data, database files, local paths, real tokens or secrets.
- Publish binaries through GitHub Releases, not through the git tree.

Related public surfaces:

- [Repository home](../README.md)
- [Knowledge base](../kb/README.md)
- [Release notes](../RELEASES.md)
- [Security policy](../SECURITY.md)
- [Support policy](../SUPPORT.md)
