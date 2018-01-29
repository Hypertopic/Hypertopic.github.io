---
title: Installer
layout: splash
header:
  overlay_image: /assets/install.png
  overlay_filter: rgba(0, 64, 0, 0.5)
---

Dans les onglets précédents, vous avez identifié les fonctionnalités qui vous intéressent et établi la liste des logiciels que vous voulez utiliser ?

Attention cependant, à l'exception de LaSuli, tous nos logiciels nécessitent d'être installés sur un serveur. L'administration système est un métier : si vous ne savez pas faire, nous vous recommandons de vous rapprocher du service informatique de votre université ou de votre entreprise.

# Logiciels de la suite Hypertopic

Les codes sources de nos logiciels sont disponibles sur GitHub. Chacun est accompagné d'instructions d'installation et d'une adresse de contact.

- [Argos](https://github.com/Hypertopic/Argos) (nécessaire si vous souhaitez utiliser Porphyry, LaSuli ou Agorae),
- [Porphyry](https://github.com/Hypertopic/Porphyry),
- [Steatite](https://github.com/Hypertopic/Steatite),
- [Cassandre](https://github.com/Hypertopic/Cassandre),
- [Agorae](https://github.com/Hypertopic/Agorae).

# Sécurité

L'authentification des usagers et leurs autorisations sont gérées par un autre logiciel – [AAAforREST](https://github.com/Hypertopic/) – qui sert de "guichet unique" des services (*HTTP reverse proxy*). Par rapport à `nginx` ou `Apache`, il permet de mettre en place les configurations classiques pour Hypertopic de manière plus simple, sans risquer de laisser ouvertes des failles. Par ailleurs, il permet, si on le souhaite, l'authentification conjointe d'usagers institutionnels (LDAP) et de collaborateurs externes.

# Adaptateur

Dans le cas où vos données doivent demeurer dans un entrepôt autre qu'Argos (base de données relationnelle, entrepôt RDF, annuaire LDAP, etc.), il est possible de développer un logiciel sur mesure appelé "adaptateur" qui présentera ces données sous une forme compatible avec le [protocole Hypertopic](https://github.com/Hypertopic/Protocol/blob/master/README.md).

[Un exemple utilisant le framework Express.js](https://github.com/Hypertopic/ldap2hypertopic) est fourni, montrant comment présenter les entrées d'un annuaire LDAP sous forme d'items Hypertopic.

# Client spécifique

Dans le cas où les traitements proposés par les logiciels clients du collectif (Porphyry, LaSuli, Agorae) seraient jugées trop génériques, il est possible de développer des clients plus adaptés à vos données. Ce développement est grandement facilité par la réutilisation de la blibliothèque logicielle "[Hypertopic Node.js Library](https://www.npmjs.com/package/hypertopic)".
