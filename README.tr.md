# PassMan Enterprise Vault Console

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Self-hosted enterprise password manager icin public release, operator dokumantasyonu, knowledge base ve support hub i.

## Bu repo neden var

Self-hosted enterprise password manager icin public release, operator dokumantasyonu, knowledge base ve support hub i.

Bu lokalize giris sayfasi, okuyucunun repoyu kisa bir dil etiketine bakarak tahmin etmemesi icin tutulur. Derin kanonik referans README.md dosyasinda kalir; bu sayfa dogru baslangic noktasini, guvenlik sinirini ve dogrulama yolunu secmek icin yeterli baglam verir.

## Kimler icin

Kurulum, operasyon, release dogrulama veya support evidence ihtiyaci olan admin ler, operator lar, security reviewer lar ve support ekipleri.

## Hizli baslangic

| Ihtiyacin varsa... | Ac |
| --- | --- |
| Latest release | [https://github.com/ucsahinn/passman/releases/latest](https://github.com/ucsahinn/passman/releases/latest) |
| Docs EN | [docs/en/README.md](docs/en/README.md) |
| Docs TR | [docs/tr/README.md](docs/tr/README.md) |
| KB EN | [kb/en/README.md](kb/en/README.md) |
| KB TR | [kb/tr/README.md](kb/tr/README.md) |
| Security policy | [SECURITY.md](SECURITY.md) |
| Support policy | [SUPPORT.md](SUPPORT.md) |
| Release notes | [RELEASES.md](RELEASES.md) |

## Repo haritasi

- README.md - release hub landing page
- docs/en/README.md / docs/tr/README.md - operator documentation
- kb/en/README.md / kb/tr/README.md - support knowledge base
- RELEASES.md - public release history
- SECURITY.md / SUPPORT.md / PRIVACY.md - trust and support policies
- assets/ - sanitized visuals and icons

## Validasyon ve release hijyeni

Commit veya yayin oncesinde linkler, Markdown, mevcut repo validasyonu ve Gitleaks kontrol edilmelidir.

Onerilen release/readiness yolu:

1. Ilgili README ve bagli dokumanlari incele.
2. Repo validasyon komutu varsa calistir.
3. Markdown linklerini ve lokal assetleri kontrol et.
4. Gitleaks veya yapilandirilmis secret scan i calistir.
5. Push sonrasi yayinin bittigini soylemeden once origin/main dogrulamasi yap.

## Guvenlik ve public scope siniri

Private kaynak kod, imzalama materyali, musteri verisi, secret, log ve installer artifact leri Git e girmez. Binary ler GitHub Releases uzerinden yayinlanir.

## Katki ve bakim

Scope, kurulum adimlari, release kurallari veya guvenlik sinirlari degistiginde lokalize sayfalari kanonik README ile ayni cizgide tut. Repo, canli urun dokumani veya public release kanitiyla desteklenmeyen iddia ekleme.

## Eksiksizlik standardi

Bu lokalize README kisa not degildir. Amac, baslangic, repo yuzeyleri, validasyon, guvenlik siniri ve kanonik referanslari aciklar.

Kanonik referans: [README.md](README.md).
