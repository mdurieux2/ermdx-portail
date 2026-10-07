# ermdx

Page d'accueil du domaine <https://ermdx.app> : la liste des applications.

| App | Adresse | Dépôt |
|---|---|---|
| Lire & Compter | <https://fun.ermdx.app> | `mdurieux2/lire-compter-samuser` |
| Affiche foot | <https://affiche.ermdx.app> | `mdurieux2/affiche-foot` |

## Publication

Fichiers statiques dans `app/`, sans étape de construction ni JavaScript, publiés par Cloudflare Pages à chaque
fusion sur `main` (dossier de sortie `app`). `app/_headers` fixe les en-têtes de sécurité (CSP stricte : rien
ne se charge depuis un autre site).

Ajouter une app : un `<li>` dans `app/index.html` (copier un existant) et son icône 192 × 192 dans `app/icons/`.

## Crédits

Polices [Bagel Fat One](https://fonts.google.com/specimen/Bagel+Fat+One) et
[Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans) (SIL Open Font License), servies depuis le site.
