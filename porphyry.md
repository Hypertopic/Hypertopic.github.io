---
title: Porphyry
layout: splash
header:
  overlay_image: /assets/porphyry.png
  overlay_filter: 0.7
  cta_label: "Essayer en ligne"
  cta_url: "http://vitraux.porphyry.org"
---

Le logiciel tire son nom de l'*arbre de Porphyre*, 
un des premiers systèmes classificatoires représentés sous forme graphique.

# Fonctionnalités

## Consulter un portfolio rassemblant plusieurs corpus et plusieurs points de vue

 - Sélectionner des items en fonction d'une rubrique ou d'un attribut contenant un terme ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/portfolio_search.feature)) 
<video width="506" height="316" controls=""><source src="/assets/porphyry_topic_search.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>

 - Consulter les attributs et les rubriques décrivant un item ([exemple](https://github.com/Hypertopic/Porphyry/blob/v7/features/item_consult.feature))
<video width="506" height="316" controls=""><source src="/assets/porphyry_item_consult.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>

 - Sélectionner des items en fonction de la place d'une rubrique dans l'arborescence
<video width="506" height="316" controls=""><source src="/assets/porphyry_tree_structure_topic_search.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>

 - Combiner les critères de sélection avec des conjonctions (`ET`), disjonctions (`OU`) ou même absences (`NON`) de rubriques ou d'attributs ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/portfolio_browse.feature))
<video width="506" height="316" controls=""><source src="/assets/porphyry_boolean_consult.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>
 
 - Croiser les rubriques en fonction des items qu'elles décrivent ([COOP 2008, fig. 7](https://hal-utt.archives-ouvertes.fr/hal-02917695))
<video width="506" height="316" controls=""><source src="/assets/porphyry_cross_topic.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>
 
 - À partir d'un item, consulter les items apparentés ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/item_get_related_items.feature))
<video width="506" height="316" controls=""><source src="/assets/porphyry_items_with_same_topic.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>

 - Partager un item au sein de son réseau social


## Éditer un item

 - Créer un item ([exemple](https://github.com/Hypertopic/Porphyry/blob/v7/features/porfolio_corpus_item_create.feature))
 
 - Décrire un item à l'aide d'attributs ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/item_set_attribute.feature))
 
 - Décrire un item à l'aide d'une rubrique (existante ou nouvelle) selon un point de vue ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/item_assign_topic.feature))
<video width="506" height="316" controls=""><source src="/assets/porphyry_item_assign_topic.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>
 
 - Commenter un item ou répondre à un commentaire (en texte libre avec des images et des liens vers des ressources externes) ([exemple](https://github.com/Hypertopic/Porphyry/blob/v7/features/item_comment.feature))
 
 - Recommander ou partager un commentaire ou une discussion
 
 - Signaler ou modérer un commentaire inapproprié
  
## Éditer un point de vue

 - Créer un point de vue
 
 - Créer une rubrique (éventuellement fille ou sœur d'une autre rubrique) ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/viewpoint_topic_create.feature))
 
 - Renommer une rubrique ([exemple](https://github.com/Hypertopic/Porphyry/blob/v7/features/viewpoint_topic_rename.feature))
 
 - Déplacer une rubrique (et ses descendantes) dans l'arborescence ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/viewpoint_topic_move.feature))
<video width="506" height="316" controls=""><source src="/assets/porphyry_viewpoint_move_topic.mp4" type="video/mp4">Votre navigateur ne sait pas afficher des vidéos au format MPEG 4.</video>
 
 - Supprimer une rubrique ([exemple](https://github.com/Hypertopic/Porphyry/blob/v7/features/viewpoint_topic_delete.feature))
 
 - Autoriser un contributeur à éditer un point de vue ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/viewpoint_authorize_editing.feature))

# Repérer des items dans l'espace

- Repérer des items sur une carte du monde, une vue aérienne (avec éventuellement des plans superposés) en fonction d'un nom de lieu

- Repérer des items sur le plan d'un édifice en fonction d'un nom de lieu et de leurs numéros de baies (méthode spécifique aux vitraux) ([exemple](https://github.com/Hypertopic/Porphyry/blob/v7/features/portfolio_browse_spatially.feature))

## Autres

- Utiliser le logiciel dans la langue de son choix ([exemples](https://github.com/Hypertopic/Porphyry/blob/v7/features/lang_set.feature))
