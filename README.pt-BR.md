# PassMan Enterprise Vault Console

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Hub publico de releases, documentacao de operador, knowledge base e suporte para um gerenciador de senhas empresarial self-hosted.

## Por que este repositorio existe

Hub publico de releases, documentacao de operador, knowledge base e suporte para um gerenciador de senhas empresarial self-hosted.

Esta pagina localizada e mantida para que leitores entendam o repositorio sem depender apenas de uma etiqueta curta de idioma. A referencia canonica profunda continua em README.md; esta pagina traz contexto suficiente para escolher a entrada, o limite de seguranca e a verificacao correta.

## Para quem e

Admins, operadores, security reviewers e equipes de suporte que precisam de instalacao, operacao, verificacao de release ou evidencia de suporte.

## Comeco rapido

| Se voce precisa... | Abra |
| --- | --- |
| Latest release | [https://github.com/ucsahinn/passman/releases/latest](https://github.com/ucsahinn/passman/releases/latest) |
| Docs EN | [docs/en/README.md](docs/en/README.md) |
| Docs TR | [docs/tr/README.md](docs/tr/README.md) |
| KB EN | [kb/en/README.md](kb/en/README.md) |
| KB TR | [kb/tr/README.md](kb/tr/README.md) |
| Security policy | [SECURITY.md](SECURITY.md) |
| Support policy | [SUPPORT.md](SUPPORT.md) |
| Release notes | [RELEASES.md](RELEASES.md) |

## Mapa do repositorio

- README.md - release hub landing page
- docs/en/README.md / docs/tr/README.md - operator documentation
- kb/en/README.md / kb/tr/README.md - support knowledge base
- RELEASES.md - public release history
- SECURITY.md / SUPPORT.md / PRIVACY.md - trust and support policies
- assets/ - sanitized visuals and icons

## Validacao e higiene de release

Antes de commit ou publicacao, revise links, Markdown, validacao existente do repo e Gitleaks.

Caminho recomendado de release/readiness:

1. Revise o README relevante e os documentos linkados.
2. Execute a validacao do repositorio quando existir um comando.
3. Verifique links Markdown e assets locais.
4. Execute Gitleaks ou o secret scan configurado.
5. Verifique origin/main depois do push antes de afirmar que a publicacao terminou.

## Limite de seguranca e escopo publico

Codigo privado, material de assinatura, dados de clientes, segredos, logs e instaladores nao vao para o Git. Binarios sao publicados via GitHub Releases.

## Contribuicao e manutencao

Mantenha as paginas localizadas alinhadas com o README canonico quando escopo, passos de instalacao, regras de release ou limites de seguranca mudarem. Nao adicione afirmacoes sem respaldo no repositorio, docs live do produto ou evidencia publica de release.

## Padrao de completude

Este README localizado nao e uma nota curta. Ele explica proposito, entrada, superficies do repositorio, validacao, limite de seguranca e referencias canonicas.

Referencia canonica: [README.md](README.md).
