# ermdx (portail)

Page d'accueil publique de https://ermdx.app : liste des apps de Michaël Durieux. Interface en français.

- Statique : `app/index.html`, `app/style.css`, polices et icônes dans `app/`. Aucun JavaScript, aucune
  ressource externe (CSP stricte dans `app/_headers`) : pas de Google Fonts en ligne, pas de traceur.
- Publication : Cloudflare Pages publie `app/` à chaque fusion sur `main`, domaine racine `ermdx.app`.
- Une app = un `<li>` avec un lien `class="app"` (icône 192 px de l'app, nom, une phrase de description,
  adresse). Ne lister que des apps publiques ; une app réservée (Cloudflare Access) n'apparaît pas ici.
- Typographie : pas de tiret cadratin ni de point médian dans les textes.
- Vérifier le rendu en clair, en sombre et à 390 px de large avant de pousser.
