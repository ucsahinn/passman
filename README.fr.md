# PassMan Enterprise Vault Console

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Hub public de releases, documentation operateur, knowledge base et support pour un gestionnaire de mots de passe entreprise autoheberge.

## Pourquoi ce depot existe

Hub public de releases, documentation operateur, knowledge base et support pour un gestionnaire de mots de passe entreprise autoheberge.

Cette page localisee est maintenue pour que le lecteur comprenne le depot sans dependre d un simple badge de langue. La reference canonique complete reste dans README.md; cette page donne assez de contexte pour choisir le bon point d entree, la limite de securite et la verification correcte.

## Pour qui

Admins, operateurs, reviewers securite et equipes support qui ont besoin d installation, exploitation, verification release ou evidence support.

## Demarrage rapide

| Si vous avez besoin de... | Ouvrez |
| --- | --- |
| Latest release | [https://github.com/ucsahinn/passman/releases/latest](https://github.com/ucsahinn/passman/releases/latest) |
| Docs EN | [docs/en/README.md](docs/en/README.md) |
| Docs TR | [docs/tr/README.md](docs/tr/README.md) |
| KB EN | [kb/en/README.md](kb/en/README.md) |
| KB TR | [kb/tr/README.md](kb/tr/README.md) |
| Security policy | [SECURITY.md](SECURITY.md) |
| Support policy | [SUPPORT.md](SUPPORT.md) |
| Release notes | [RELEASES.md](RELEASES.md) |

## Carte du depot

- README.md - release hub landing page
- docs/en/README.md / docs/tr/README.md - operator documentation
- kb/en/README.md / kb/tr/README.md - support knowledge base
- RELEASES.md - public release history
- SECURITY.md / SUPPORT.md / PRIVACY.md - trust and support policies
- assets/ - sanitized visuals and icons

## Validation et hygiene de release

Avant commit ou publication, verifiez les liens, le Markdown, la validation existante du depot et Gitleaks.

Parcours release/readiness recommande:

1. Relire le README pertinent et les documents lies.
2. Executer la validation du depot lorsqu une commande existe.
3. Verifier les liens Markdown et les assets locaux.
4. Executer Gitleaks ou le secret scan configure.
5. Verifier origin/main apres le push avant d annoncer que la publication est terminee.

## Limite securite et perimetre public

Code prive, elements de signature, donnees client, secrets, logs et installateurs ne vont pas dans Git. Les binaires sont publies via GitHub Releases.

## Contribution et maintenance

Gardez les pages localisees alignees avec le README canonique lorsque le perimetre, les etapes d installation, les regles de release ou les limites de securite changent. N ajoutez pas d affirmations sans preuve dans le depot, les docs live du produit ou les elements publics de release.

## Standard de completude

Ce README localise n est pas une note courte. Il explique le but, l entree rapide, les surfaces du depot, la validation, la limite de securite et les references canoniques.

Reference canonique: [README.md](README.md).
