HYDROURBAN DZ - VITRINE STATIQUE POUR GITHUB PAGES

CONTENU
- index.html : site complet, une seule page
- style.css : interface responsive et animations CSS
- app.js : interactions locales, filtre des 50 produits, mini-simulateur
- assets/ : illustrations SVG generiques issues du dossier public du projet fourni
- catalogue.json : liste illustrative avec les tarifs indicatifs precedemment fixes
- .nojekyll : publication directe des fichiers

AVANT DE PUBLIER
1. Cette vitrine ne contient ni serveur Next.js, ni Prisma, ni base PostgreSQL, ni comptes utilisateurs, ni stocks, ni commande, ni PDF reel.
2. Tous les tarifs sont des estimations commerciales fournies pour la demonstration et non des offres contractuelles.
3. Le code HTML/CSS/JavaScript de la vitrine est public et consultable par chaque visiteur. Le code serveur de l'application originale n'est PAS inclus.
4. Les filtres du catalogue fonctionnent dans le navigateur. Le simulateur est pedagogique : 3 m par canal, et floor(300 cm / espacement), sans calcul de pompe, debit ni verification agronomique.
5. Cette vitrine ne collecte aucune information personnelle. Pas de contact par formulaire ni de cookies.
6. GitHub Pages n'est pas autorise pour faire tourner une boutique en ligne ou un service SaaS commercial. Utiliser cette page uniquement comme presentation / demonstration statique.

MISE EN LIGNE
1. Ouvrir un compte GitHub puis creer un depot PUBLIC nomme hydrourban-vitrine-demo.
2. Dans le depot, cliquer Add file > Upload files, puis envoyer LES FICHIERS ET DOSSIERS DU ZIP DECOMPRESSE (PAS LE ZIP NI LE PROJET NEXT.JS).
3. Commit changes.
4. Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main / (root) > Save.
5. URL attendue: https://VOTRE-IDENTIFIANT.github.io/hydrourban-vitrine-demo/
   Attendre la publication et utiliser Visit site dans Settings > Pages.
6. Pour mettre a jour, remplacer les fichiers statiques du depot (ne jamais publier .env, prisma, src, node_modules, dumps).

TEST LOCAL
Ouvrir index.html dans un navigateur. La vitrine est autonome pour l'essentiel ; les polices en ligne exigent Internet mais les polices systeme servent de secours.

POUR UNE APPLICATION COMPLETE (comptes, devis, stocks et PDF), il faut un serveur Next.js et PostgreSQL, pas GitHub Pages.
