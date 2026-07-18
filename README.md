# Plutus — releases publiques

Ce dépôt héberge **les releases publiques de Plutus**, l'espace de travail du
conseiller en gestion de patrimoine (application Windows, 100 % locale).

> **Le code source de l'application n'est pas publié ici** — ni ailleurs :
> Plutus est développé dans un dépôt privé. Ce dépôt ne contient que les
> installeurs publiés et le fichier `version.json`. Il est normal qu'il
> paraisse presque vide.

## Télécharger Plutus

- Dernière version : **[Releases → latest](https://github.com/venum78160/Plutus/releases/latest)**
- Lien direct de l'installeur :
  [`Plutus-Installation.exe`](https://github.com/venum78160/Plutus/releases/latest/download/Plutus-Installation.exe)
- Site public (présentation, démonstration, installation) :
  **<https://venum78160.github.io/plutus-site/>**

## Systèmes supportés

- Windows 10 ou 11 (64 bits)
- Microsoft Word ou LibreOffice pour la conversion des documents en PDF

## `version.json`

Le fichier [`version.json`](version.json) est réécrit automatiquement à chaque
release. C'est la **source publique de vérité** de la version courante :

| Champ | Rôle |
|---|---|
| `version` | Numéro publié (semver) |
| `url` | Page de la release |
| `url_exe` | Lien direct de l'installeur |
| `notes` | Résumé des nouveautés |

Il alimente à la fois la bannière de mise à jour intégrée à l'application et
la page de téléchargement du site public — les deux affichent donc toujours la
même version que l'installeur publié ici.
