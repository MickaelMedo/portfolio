---
title: Plan infra réseau
publishDate: 2024-04-19 20:00:00
img: /assets/Plan infra réseau.jpg
img_alt: plan infra
description: |
  Conception du plan d'infrastructure réseau et mise en place de VLAN
tags:
  - Dessin
  - Réseau
  - VLAN
---

## Plan infrastructure

> Conception et Mise en Place d'un Plan d'Infrastructure Réseau.

Dans le cadre d'un projet de modernisation et d'optimisation de l'infrastructure réseau de mon entreprise, j'ai été chargé de concevoir et de mettre en place un plan complet, de A à Z, pour répondre aux besoins actuels et futurs en matière de connectivité.

La première étape a été d'évaluer l'état actuel du réseau. Cependant, une difficulté majeure est survenue : presque aucune prise RJ45 n'était numérotée, rendant l'identification des connexions physique à leurs emplacements respectifs impossible. Mais pour remédier à cette situation, j'ai utilisé un testeur de liaison RJ45 pour tracer chaque prise jusqu'à son emplacement sur le patch panel. Cela a permis de créer une cartographie précise des connexions physiques.

#### Configuration du Pare-feu

La création et la configuration des VLAN sur le pare-feu SonicWall ont également été nécessaires pour garantir une sécurité optimale et une gestion efficace du trafic réseau. De plus, j'ai dû effectuer le routage pour les différents VLAN afin d'assurer une connectivité fluide entre les différentes zones du réseau, permettant ainsi aux utilisateurs d'accéder aux ressources nécessaires tout en maintenant une segmentation logique.

#### Restauration et Configuration de Switchs

Une autre étape cruciale a été la restauration des anciens switchs, suivie de leur reconfiguration. Cela impliquait l'ajout et la configuration de VLAN pour segmenter le réseau en différentes zones, notamment pour les ordinateurs, les imprimantes et le réseau WiFi.

Une fois les VLAN configurés, j'ai procédé au branchement des câbles RJ45 sur les ports des switchs dédiés à chaque VLAN. Cela a permis d'assurer une séparation logique et sécurisée du trafic réseau.

Parallèlement, j'ai effectué des agrégations de liens sur les NAS afin d'augmenter le débit et d'optimiser les performances du stockage réseau, assurant ainsi une meilleure fluidité des transferts de données.

#### Documentation et Finalisation

Enfin, j'ai réalisé une documentation détaillée de l'ensemble du plan d'infrastructure réseau, en utilisant l'outil de création de diagrammes Draw.io. Chaque prise a été répertoriée avec son numéro et son emplacement sur le switch, permettant une gestion et une maintenance simplifiées à l'avenir.

#### Conclusion

Ce projet de conception et de mise en place d'un plan d'infrastructure réseau a représenté un défi stimulant, nécessitant une résolution créative des problèmes et une expertise approfondie en matière de réseau. Grâce à une approche méthodique et à un travail efficace, le résultat final est un réseau performant, sécurisé et prêt à répondre aux besoins de l'entreprise pour les années à venir.