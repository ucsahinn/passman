# PassMan Enterprise Vault Console

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Oeffentlicher Release-, Operator-Dokumentations-, Knowledge-Base- und Support-Hub fuer einen selbst gehosteten Enterprise Password Manager.

## Warum dieses Repository existiert

Oeffentlicher Release-, Operator-Dokumentations-, Knowledge-Base- und Support-Hub fuer einen selbst gehosteten Enterprise Password Manager.

Diese lokalisierte Startseite wird gepflegt, damit Leser das Repository nicht nur ueber ein kurzes Sprach-Badge verstehen muessen. Die tiefe kanonische Referenz bleibt in README.md; diese Seite enthaelt genug Kontext, um den richtigen Einstieg, die Sicherheitsgrenze und die Verifikation zu waehlen.

## Fuer wen es gedacht ist

Admins, Operator, Security Reviewer und Support-Teams, die Installation, Betrieb, Release-Pruefung oder Support-Evidence brauchen.

## Schnellstart

| Wenn du brauchst... | Oeffne |
| --- | --- |
| Latest release | [https://github.com/ucsahinn/passman/releases/latest](https://github.com/ucsahinn/passman/releases/latest) |
| Docs EN | [docs/en/README.md](docs/en/README.md) |
| Docs TR | [docs/tr/README.md](docs/tr/README.md) |
| KB EN | [kb/en/README.md](kb/en/README.md) |
| KB TR | [kb/tr/README.md](kb/tr/README.md) |
| Security policy | [SECURITY.md](SECURITY.md) |
| Support policy | [SUPPORT.md](SUPPORT.md) |
| Release notes | [RELEASES.md](RELEASES.md) |

## Repository-Karte

- README.md - release hub landing page
- docs/en/README.md / docs/tr/README.md - operator documentation
- kb/en/README.md / kb/tr/README.md - support knowledge base
- RELEASES.md - public release history
- SECURITY.md / SUPPORT.md / PRIVACY.md - trust and support policies
- assets/ - sanitized visuals and icons

## Validierung und Release-Hygiene

Vor Commit oder Veroeffentlichung sollten Links, Markdown, vorhandene Repo-Validierung und Gitleaks geprueft werden.

Empfohlener Release-/Readiness-Pfad:

1. Relevante README und verlinkte Dokumente pruefen.
2. Die Validierung des Repositories ausfuehren, wenn ein Befehl vorhanden ist.
3. Markdown-Links und lokale Assets kontrollieren.
4. Gitleaks oder den konfigurierten Secret Scan ausfuehren.
5. Nach dem Push origin/main pruefen, bevor Veroeffentlichung als erledigt gemeldet wird.

## Sicherheits- und Public-Scope-Grenze

Private Source, Signing-Material, Kundendaten, Secrets, Logs und Installer-Artefakte gehoeren nicht in Git. Release-Binaries werden ueber GitHub Releases bereitgestellt.

## Mitwirken und Pflege

Halten Sie lokalisierte Seiten synchron mit der kanonischen README, wenn sich Scope, Installationsschritte, Release-Regeln oder Sicherheitsgrenzen aendern. Fuegen Sie keine Aussagen hinzu, die nicht durch Repository, Live-Produktdokumentation oder oeffentliche Release-Nachweise gedeckt sind.

## Vollstaendigkeitsstandard

Diese lokalisierte README ist keine Kurznotiz. Sie erklaert Zweck, Einstieg, Repository-Flaechen, Validierung, Sicherheitsgrenze und kanonische Referenzen.

Kanonische Referenz: [README.md](README.md).
