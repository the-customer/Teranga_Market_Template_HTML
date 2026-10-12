# Teranga Market — Template HTML/CSS étudiant

**M. Aly Tall Niang · Projet de synthèse Vue 3**

## Démarrage

1. Décompresser l’archive entière.
2. Ouvrir `index.html` dans un navigateur : c’est la boutique.
3. Ouvrir `sommaire.html` pour parcourir toutes les familles d’écrans.
4. Lire `guide.html` pour le travail à réaliser sur chacune des 24 demandes.

Aucune installation, aucune commande npm, aucune connexion Internet et aucun serveur ne sont nécessaires pour consulter le template. Un serveur local de votre choix reste facultatif.

## Contenu

- **96 pages HTML** : accueil, catalogue grille/liste, cinq catégories, dix-neuf fiches de produits actifs, panier, commande, suivi, administration et états visuels.
- **20 formulaires de modification** : chaque bouton Modifier ouvre le produit correspondant.
- **10 détails de commandes** : les liens du tableau et des cartes ouvrent les bonnes fiches.
- **2 feuilles CSS** : `assets/css/styles.css` (charte du projet) et `assets/css/template.css` (variantes statiques et compléments).
- Illustrations SVG et logo locaux, repris de la version précédente du projet.
- Aucun fichier JavaScript, Vue, dépendance, backend ou base JSON fourni dans ce pack de design.

## Ce qui fonctionne sans JavaScript

La navigation entre les pages, les champs natifs, les sections `details`, les styles responsive et l’ouverture des aperçus de modales/tiroir avec la cible CSS. Les variantes Grille, Liste, Retrait, Livraison et Sombre sont des pages distinctes, pas des changements d’état de l’application.

## Ce qui reste à programmer

TOUTES les actions métier : ajout au panier, quantités, prix, remises, filtres, tri, validation, enregistrement, suivi réel, changements de statut, stock, notifications temporaires, focus, chargements, persistance et erreurs.

Les boutons `data-action` sont volontairement de type `button`. Ils n’exécutent aucune action. Les formulaires ne sont pas câblés. Changer un champ ne change pas les totaux. Aucun clic ne crée une commande, même lorsqu’on ouvre la page de confirmation.

## Utilisation dans Vue

- Extraire les éléments `data-component` en composants monofichiers.
- Copier le contenu HTML nécessaire dans les templates, pas les enveloppes `html/head/body`.
- Centraliser les deux CSS dans le projet Vue et ajuster les chemins d’images.
- Remplacer les liens HTML par des routes.
- Construire les layouts pour ne plus répéter en-tête et pied de page.
- Relier les `data-action` aux gestionnaires d’événements.
- Transformer les constantes en données réactives, puis les charger depuis JSON Server.
- Les commentaires `DEMANDE` et le guide indiquent le travail attendu, sans donner le corrigé JavaScript.

## Accessibilité à compléter dans l’application

Les pages ont des titres, labels, textes alternatifs, repères sémantiques et liens d’évitement. Les modales CSS sont des aperçus : le piégeage du focus, sa restitution, la fermeture par Échap, l’inertie du fond et l’ouverture pilotée doivent être gérés dans les composants Vue. Aucun autofocus caché n’est fourni comme substitution à la directive demandée.

## Données et limites

Toutes les données affichées sont fictives. L’administration est volontairement accessible : aucune authentification. L’archive représente le design, pas un logiciel de commerce prêt à l’emploi.

Le scénario du panier utilise 1 sac de riz, 2 kg d’oignons et 1 sachet de bissap : sous-total 20 100 FCFA, remise TERANGA10 de 2 010 FCFA, total retrait 18 090 FCFA, total livré à Ouakam 20 090 FCFA. Ces mêmes montants figurent dans la confirmation et TM-DEMO-001. Les autres commandes servent à montrer les différents statuts.

`VERIFICATION.md` décrit les contrôles réellement exécutés sur cette archive.
