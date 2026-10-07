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

Police [Geist](https://vercel.com/font) (SIL Open Font License), servie depuis le site. Le logo (lettre « e »
et mot « ermdx ») est tracé à partir de Geist Semibold, en SVG, sans dépendance à la police.
