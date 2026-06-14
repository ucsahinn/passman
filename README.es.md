# PassMan Enterprise Vault Console

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Hub publico de releases, documentacion de operador, knowledge base y soporte para un password manager empresarial autohospedado.

## Por que existe este repositorio

Hub publico de releases, documentacion de operador, knowledge base y soporte para un password manager empresarial autohospedado.

Esta portada localizada se mantiene para que el lector entienda el repositorio sin depender de una etiqueta de idioma corta. La referencia canonica profunda sigue en README.md; esta pagina contiene suficiente contexto para elegir el punto de entrada, el limite de seguridad y la verificacion correcta.

## Para quien es

Admins, operadores, security reviewers y equipos de soporte que necesitan instalacion, operacion, verificacion de release o evidencia de soporte.

## Inicio rapido

| Si necesitas... | Abre |
| --- | --- |
| Latest release | [https://github.com/ucsahinn/passman/releases/latest](https://github.com/ucsahinn/passman/releases/latest) |
| Docs EN | [docs/en/README.md](docs/en/README.md) |
| Docs TR | [docs/tr/README.md](docs/tr/README.md) |
| KB EN | [kb/en/README.md](kb/en/README.md) |
| KB TR | [kb/tr/README.md](kb/tr/README.md) |
| Security policy | [SECURITY.md](SECURITY.md) |
| Support policy | [SUPPORT.md](SUPPORT.md) |
| Release notes | [RELEASES.md](RELEASES.md) |

## Mapa del repositorio

- README.md - release hub landing page
- docs/en/README.md / docs/tr/README.md - operator documentation
- kb/en/README.md / kb/tr/README.md - support knowledge base
- RELEASES.md - public release history
- SECURITY.md / SUPPORT.md / PRIVACY.md - trust and support policies
- assets/ - sanitized visuals and icons

## Validacion e higiene de release

Antes de commit o publicacion, revisa links, Markdown, validacion existente del repo y Gitleaks.

Ruta recomendada de release/readiness:

1. Revisar el README relevante y los documentos enlazados.
2. Ejecutar la validacion del repositorio cuando exista un comando.
3. Comprobar links Markdown y assets locales.
4. Ejecutar Gitleaks o el secret scan configurado.
5. Verificar origin/main despues del push antes de afirmar que la publicacion termino.

## Limite de seguridad y alcance publico

Codigo privado, material de firma, datos de clientes, secretos, logs e instaladores no van en Git. Los binarios se publican via GitHub Releases.

## Contribucion y mantenimiento

Mant?n las paginas localizadas alineadas con el README canonico cuando cambien el alcance, los pasos de instalacion, las reglas de release o los limites de seguridad. No agregues afirmaciones que no esten respaldadas por el repositorio, docs live del producto o evidencia publica de release.

## Estandar de completitud

Este README localizado no es una nota corta. Explica proposito, entrada, superficies del repositorio, validacion, limite de seguridad y referencias canonicas.

Referencia canonica: [README.md](README.md).
