# Atelier Noyer — site vitrine B2B

Site statique responsive en français/arabe pour un atelier de gravure laser en Tunisie.

## Contenu
- Catalogue de 12 concepts produits avec photos, filtres et fiches produit en fenêtre modale.
- Prix indicatifs modifiables dans `script.js`.
- Formulaire de demande de devis préparant un message WhatsApp.
- Sections hôtels/maisons d'hôtes, cafés/restaurants, entreprises, cadeaux.
- Mise en page responsive mobile/ordinateur.

## AVANT PUBLICATION — obligatoire
1. Ouvrir `script.js`.
2. Remplacer `21600000000` dans `WHATSAPP_NUMBER` par le numéro WhatsApp professionnel, chiffres seulement, indicatif pays inclus. Exemple de format : `216XXXXXXXX`.
3. Vérifier chaque prix et chaque description. Les prix sont des estimations de départ, pas des tarifs confirmés.
4. Les images du dossier `assets/` sont des illustrations (SVG) de chaque produit. Dès que vous avez de vraies photos de vos réalisations, remplacez-les dans `assets/` (ou changez les chemins dans `script.js` et `index.html`).
5. Le nom « Atelier Noyer » est une proposition créative. Vérifier la disponibilité du nom commercial et du domaine avant de l'adopter officiellement.

## Tester sur votre ordinateur
- Décompresser le ZIP.
- Double-cliquer sur `index.html` pour l'ouvrir dans le navigateur.
- Le catalogue fonctionne sans serveur. Le formulaire WhatsApp ne s'ouvrira correctement qu'après configuration du numéro.

## Publication gratuite avec GitHub Pages
1. Créez un nouveau dépôt public GitHub nommé `atelier-noyer` (ou autre nom).
2. Importez `index.html`, `style.css`, `script.js`, `README.md` et le dossier `assets`.
3. Dans le dépôt, ouvrez **Settings → Pages**.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**, puis branche `main` et dossier `/ (root)`, puis **Save**.
5. Attendez la fin du déploiement et ouvrez l'URL affichée dans Settings → Pages. L'adresse sera du type `https://VOTRE-NOM.github.io/atelier-noyer/`.
6. Vous pourrez ensuite connecter un domaine personnalisé depuis les paramètres Pages si vous en achetez un.

## Limites de cette version
- C'est un site vitrine/catalogue, pas une boutique avec paiement en ligne ni une base de données.
- Les demandes sont envoyées par WhatsApp, sans sauvegarde dans le site.
- Les photos sont des images d'ambiance/exemples, elles ne garantissent pas que les produits exacts illustrés soient ceux que l'atelier fabriquera.
- Avec une diode 10W, validez la matière et les tests de sécurité avant de proposer chaque produit. Ne gravez/coupez pas du PVC.
