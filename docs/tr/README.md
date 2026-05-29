# PassMan Türkçe Doküman Ana Sayfa

Bu sayfa PassMan Enterprise Vault Console için Türkçe operatör haritasıdır. Kurulumdan güvenli işletime kadar en kısa yolu göstermek için hazırlanmıştır.

## Önerilen Sıra

| Adım | Rehber | Sonuç |
| --- | --- | --- |
| 1 | [Genel bakış](overview.md) | Self-hosted server modeli ve bileşen sınırları anlaşılır. |
| 2 | [Windows Server kurulumu](install-windows-server.md) | MSI kurulur, servis durumu ve tarayıcı erişimi doğrulanır. |
| 3 | [İlk kurulum, owner ve lisans](first-run-owner-license.md) | Owner profili oluşturulur, kasa açılır ve lisans durumu uygulanır. |
| 4 | [Public host ve HTTPS](public-host-https-certificate.md) | Host, zorunlu sertifika paketi ve tarayıcı güven yolu yapılandırılır. |
| 5 | [Denetim ve güvenlik duruşu](audit-and-security-posture.md) | Skor sinyalleri, denetim zinciri ve öncelikli aksiyonlar incelenir. |
| 6 | [Tarayıcı eklentisi](browser-extension.md) | Onaylı tarayıcılar eşleştirilir; autofill, badge ve save/update davranışı anlaşılır. |
| 7 | [Active Directory ajanı](active-directory-agent.md) | PassMan DC Agent Service kurulur veya onarılır, sync tree sağlığı doğrulanır. |
| 8 | [Paylaşım ve offline decrypter](sharing-and-offline-decrypter.md) | Seçili kayıtlar ve dosyalar süre sonu, kullanım limiti ve alıcı modeliyle paketlenir. |
| 9 | [Yedekleme ve geri yükleme](backups-and-restore.md) | Şifreli yedek, bütünlük ve geri yükleme prosedürü hazırlanır. |
| 10 | [Güncelleme Merkezi](update-center.md) | İmzalı manifest, release asset'leri ve MSI update akışı doğrulanır. |

## Hemen Cevap Gerekiyorsa

| Soru | Buradan başla |
| --- | --- |
| PassMan bulut servisi mi? | [SSS](faq.md) |
| Server'i hangi dosya kurar? | [Windows Server kurulumu](install-windows-server.md) |
| Tarayıcı neden sertifika uyarısı veriyor? | [Public host ve HTTPS](public-host-https-certificate.md) |
| Güvenlik skoru neden düşük? | [Denetim ve güvenlik duruşu](audit-and-security-posture.md) |
| Update neden yüzde 76 civarında kaldı? | [Bilgi bankası: update](../../kb/tr/update-stuck-76.md) |
| DC Agent servisi neden bağlanmıyor? | [Bilgi bankası: DC Agent](../../kb/tr/dc-agent-service.md) |
| Support'a ne gönderebilirim? | [Sorun giderme](troubleshooting.md) ve [Destek politikası](../../SUPPORT.md) |

## Public Güvenlik Sınırı

Public ticket, yorum veya dokümana gerçek secret, ana parola, AD bind parolası, agent token, lisans private materyali, database, yedek, PFX/P12 dosyası veya private key eklemeyin.

Örneklerde `<PASSMAN_URL>`, `<SERVER_HOST>`, `<AGENT_ID>`, `<AGENT_TOKEN>`, `<LICENSE_CODE>` ve `<REDACTED>` gibi placeholder kullanın.

İlgili sayfalar: [Repo ana sayfası](../../README.md), [Bilgi bankası](../../kb/tr/README.md), [Release notları](../../RELEASES.md), [Güvenlik politikası](../../SECURITY.md).
