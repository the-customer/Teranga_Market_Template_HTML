# Vérifications du template HTML/CSS

## Contenu contrôlé

- 96 fichiers HTML.
- 3308 références href vérifiées, y compris les cibles des ancres.
- 633 occurrences d’images vérifiées dans les pages.
- Tous les fichiers CSS, images et icônes sont locaux.
- Aucun fichier JavaScript, Vue, paquet npm ou police externe n’est distribué.
- Aucune balise script, attribut d’événement inline ou directive Vue dans le balisage actif.
- Aucun script ni chargement distant trouvé dans les illustrations SVG.
- Chaque page possède un titre principal ; tous les champs ont un nom accessible.
- Aucun identifiant HTML dupliqué, aucune référence locale manquante détectés.

## Rendu dans le navigateur

Les 96 pages ont été rendues dans Chromium avec le JavaScript de page désactivé, à deux formats :

- Ordinateur : 1 440 × 1 000 pixels.
- Mobile : 390 × 844 pixels.

Soit 192 rendus contrôlés automatiquement. Après correction de la grille du panier : aucune image manquante, aucun débordement horizontal de la page et aucun champ sans nom accessible détectés. Les tableaux et les rayons défilent à l’intérieur de leurs conteneurs lorsque nécessaire.

Les captures de pages représentatives ont également été examinées visuellement : accueil, administration, commande, panier mobile et tiroir panier.

## Interactions d’aperçu contrôlées

Sans JavaScript de page : ouverture et fermeture du tiroir panier, de la fenêtre de recherche et d’une modale de confirmation par liens et cibles CSS.

Les boutons métier restent volontairement inactifs : le contrôle a vérifié qu’un clic sur Augmenter et Appliquer ne modifie ni le panier ni les montants. Ces comportements sont précisément ceux que les étudiants doivent écrire.

## Conditions et limites de ces vérifications

La navigation directe vers des fichiers file:// et vers un serveur HTTP local est bloquée par la politique Chromium de l’environnement de génération. Les rendus ont donc été réalisés à partir des octets HTML, CSS et images locaux, injectés dans une page de test. Cette intégration temporaire des ressources concerne uniquement les contrôles ; les fichiers livrés utilisent leurs vrais chemins relatifs.

Les chemins et les ancres ont été contrôlés séparément sur les fichiers réels. Les validations ne constituent ni un audit complet d’accessibilité, ni un test de tous les navigateurs, ni une recette métier : aucune logique métier n’est implémentée dans ce template.

Le piégeage du focus, sa restitution, la fermeture par Échap, la gestion de l’inertie du fond, les annonces dynamiques et les traitements API doivent être réalisés dans les composants Vue.
