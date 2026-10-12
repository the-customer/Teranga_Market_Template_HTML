# Les 24 demandes — points de départ

## 01. Une boutique qui représente mon commerce

Écran : `index.html`

À réaliser : Lier le nom, les catégories et les images. Répéter les catégories et les produits mis en avant.

Notions : v-bind, attributs dynamiques, CSS, listes.

## 02. Comprendre la disponibilité des produits

Écran : `produits/02-oignons.html`

À réaliser : Extraire ProductCard et les badges ; déclarer les props et leurs validateurs ; rendre les prix et stocks dynamiques.

Notions : Props, validateurs, computed, conditions.

## 03. Trouver rapidement le bon produit

Écran : `boutique.html`

À réaliser : Relier les champs aux filtres ; combiner recherche, catégorie, disponibilité et tri ; calculer le nombre de résultats.

Notions : reactive, ref, computed, v-model.

## 04. Une fiche détaillée par produit

Écran : `produits/01-riz.html`

À réaliser : Lire l’identifiant de route ; charger le produit ; réagir à son changement ; afficher chargement et introuvable.

Notions : Vue Router, API, lifecycle, watch.

## 05. Préparer son panier simplement

Écran : `panier.html`

À réaliser : Créer le store panier ; ajouter, fusionner et retirer les lignes ; contrôler les quantités et calculer les montants.

Notions : Pinia, événements, computed.

## 06. Un panier accessible partout

Écran : `exemples/tiroir-panier.html`

À réaliser : Extraire BaseDrawer et CartContent ; piloter l’ouverture ; gérer le clavier et les événements de fermeture.

Notions : Slots, props, emits, ref.

## 07. Récompenser les clients fidèles

Écran : `panier.html`

À réaliser : Vérifier les codes ; appliquer le meilleur avantage ; effacer les anciens messages au changement de saisie.

Notions : computed, watch, Pinia.

## 08. Connaître le client

Écran : `commande.html`

À réaliser : Valider les données avec useForm de VeeValidate ; empêcher les doubles envois ; conserver le formulaire en cas d’erreur.

Notions : Formulaires, useForm, API POST.

## 09. Des frais selon le quartier

Écran : `commande-retrait.html`

À réaliser : Charger les quartiers ; recalculer la livraison ; afficher ou retirer l’adresse selon le mode choisi.

Notions : API, v-model, computed, watch.

## 10. Confirmer et suivre la commande

Écran : `suivi-commande.html`

À réaliser : Créer la référence ; afficher la commande enregistrée ; rechercher et actualiser le suivi.

Notions : Vue Router, API, rendu conditionnel.

## 11. Un espace dédié à la gestion

Écran : `admin/index.html`

À réaliser : Construire PublicLayout et AdminLayout ; utiliser les routes imbriquées et les slots de PagePanel.

Notions : Layouts, slots avancés, RouterView.

## 12. Ajouter un produit

Écran : `admin/produit-ajouter.html`

À réaliser : Valider les champs ; afficher l’aperçu de l’image ; POST puis synchroniser la liste.

Notions : useForm, formulaires, API.

## 13. Corriger un produit

Écran : `admin/produits-modifier/01.html`

À réaliser : Réutiliser ProductForm en modification ; copier les valeurs ; PATCH ; ne pas modifier la prop directement.

Notions : Props, watch, emits, API PATCH.

## 14. Désactiver un produit

Écran : `admin/produits-inactifs.html`

À réaliser : Confirmer la désactivation ; PATCH ; exclure les inactifs de la boutique ; proposer la réactivation.

Notions : Événements, computed, conditions.

## 15. Choisir la présentation des commandes

Écran : `admin/commandes-cartes.html`

À réaliser : Transformer les deux présentations en composants dynamiques ; conserver la préférence.

Notions : Dynamic Components, Pinia, CSS.

## 16. Traiter les commandes

Écran : `admin/commandes/demo-001.html`

À réaliser : Filtrer les statuts ; n’autoriser que les transitions prévues ; annuler avec restitution de stock.

Notions : API, Pinia, conditions, événements.

## 17. Des notifications cohérentes

Écran : `exemples/composants.html#notifications`

À réaliser : Fournir le service avec provide et le consommer avec inject ; gérer fermeture et durée de vie.

Notions : Provide & Inject, reactive, lifecycle.

## 18. Des champs prêts pour la saisie

Écran : `exemples/recherche.html`

À réaliser : Créer v-focus ; utiliser une référence de template pour le premier champ invalide ; gérer le DOM après rendu.

Notions : Custom Directives, Template Refs, nextTick.

## 19. Retrouver ses préférences

Écran : `admin/preferences.html`

À réaliser : Créer useTheme ; garder une source unique ; persister thème et modes avec un watcher.

Notions : Composables, watch, Pinia, CSS.

## 20. Charger seulement ce qui est utile

Écran : `exemples/module-chargement.html`

À réaliser : Différer les routes admin et le composant StatisticsPanel ; prévoir un état de chargement et un état d’échec.

Notions : Async Components, imports dynamiques.

## 21. Voir les indicateurs

Écran : `admin/statistiques.html`

À réaliser : Calculer les cartes, les dernières commandes et les cinq produits les plus demandés.

Notions : computed, Pinia, API.

## 22. Réutiliser les comportements

Écran : `exemples/erreur-api.html`

À réaliser : Créer useFetch et useDebounce ; relancer les requêtes ; éviter les données dupliquées ; nettoyer les effets.

Notions : Composables, watchers, lifecycle.

## 23. Des fenêtres réutilisables

Écran : `exemples/modales.html`

À réaliser : Créer BaseModal avec slots nommés et scoped slots ; props validées ; emits ; focus et état pending.

Notions : Slots avancés, emits, Template Refs.

## 24. Une application cohérente

Écran : `exemples/prix-modifie.html`

À réaliser : Synchroniser les stores ; revérifier les prix et stocks ; bloquer les paniers invalides ; demander une nouvelle confirmation.

Notions : Pinia, API, Vue Router, computed.

