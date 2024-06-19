---
title: Site de garage automobile
publishDate: 2023-07-18 00:00:00
img: /portfolio/assets/AAAA.PNG
img_alt: Capture d'écran du site du garage V.Parrot
description: |
  J'ai créé pour ma soutenance un site web complet pour un garage automobile, offrant à la fois une vitrine en ligne pour les services de réparations, ainsi qu'un espace administrable pour la gestion interne de l'entreprise.
tags:
  - React.js
  - Symfony
  - EasyAdmin
---

## Garage Vincent Parrot (Projet d'étude)

> Analyse et conception :

Vous pouvez accéder au site en cliquant sur le lien suivant, <a href="https://www.garage-parrot.horizonduweb.fr">"Site de garage automobile"</a>.

En débutant la lecture du cahier de charges qui expliquait le contexte, l'histoire de l'entreprise et les besoins du client, j'ai pu analyser les fonctionnalités. Le patron , M. Parrot, voulait tout d'abord un site web pour accroître sa visibilité sur le web et trouver de nouveaux clients. Il souhaitait avoir une partie administrateur sur son site afin de pouvoir gérer le contenu en compagnie de son équipe. M. Parrot voulait créer les comptes de ses employés, gérer les services de réparations et être en mesure de modifier les horaires d'ouverture du garage.

Les employés du garge pouvaient également gérer les véhicules d'occasion, en ajoutant de nouvelles voitures disponible à la vente avec tous leurs descriptifs et en pouvant les supprimer. Ils étaient également en charge d'ajouter et de modérer les avis des clients.

Les visiteurs pouvaient consulter le site ainsi que les véhicules d'occasion, les services de réparation avec leurs prix et les horaires d'ouvertures pour prévoir leur passage au garage.

Il était précisé dans le cahiers des charges qu'il devait y avoir un système de filtre au niveau des véhicules d'occasion, sans nécessité de recharger la page, afin de faciliter la recherche des visiteurs et d'offir une navigation plus fluide et plus ergonomique. j'ai ajouté de ma propre initiative un système de notation par étoiles pour que les clients puissent évaluer sur une échelle de 1 à 5 les prestations du garage.

Je me suis aidé de Figma un logiciel pour créer des maquettes, afin de construire une vue d'ensemble de l'application, déterminer l'emplacement des boutons, du logo, ect. Cliquez sur le lien suivant pour accéder à la charte graphique du projet et à l'identité visuelle du garage, <a href="https://www.figma.com/file/EqJ4J6EtzmCnGsEqciJ61K/Wireframe--Garage-V.-Parrot?type=design&node-id=6%3A3&mode=dev&t=ussYztuMDy3ReRfl-1">"Charte graphique du projet."</a>

J'ai réalisé ces maquettes en format mobile puis en format ordinateur. Cliquez sur le lien pour accéder à la maquette version mobile, <a href="https://www.figma.com/file/EqJ4J6EtzmCnGsEqciJ61K/Wireframe--Garage-V.-Parrot?type=design&node-id=0%3A1&mode=dev&t=ussYztuMDy3ReRfl-1">"Maquette version mobile."</a>

<a href="https://www.figma.com/file/EqJ4J6EtzmCnGsEqciJ61K/Wireframe--Garage-V.-Parrot?type=design&node-id=6%3A2&mode=dev&t=ussYztuMDy3ReRfl-1">"Maquette version ordinateur."</a>

Je me suis inspirée des sites automobile existants pour respecter les codes couleurs et l'ambiance de style. Pour la gestion de projet j'ai utilisé la méthode kanban à l'aide de Trello, inscrivez-vous sur "Trello" et rejoignez-moi sur ce lien pour explorer le tableau qui a organisé tous mon travail, <a href="https://trello.com/invite/b/iDKJ1cAk/ATTI690d173f7015fd377efbe5b57e2d050282464D01/creation-de-site-garage-v-parrot">"Tableau Trello"</a>. Trello est un logiciel de gestion de projet qui permet d'organiser le flux de travail avec des cartes à déplacer selon l'avancement du projet. Ce logiciel est fait aussi pour le travail collaboratif.

### Développement et implémentation :

J'ai utilisé un ensemble d'outils spéciaux sur mon ordinateur pour construire le site, un peu comme un menuisier utilise ses outils pour fabriquer un meuble. j'ai utilisé Symfony et Composer, des outils principaux , et ils m'ont aidée à structurer et à organiser le projet de manière efficace. Pour l'aspect visuel du site j'ai utilisé Twig , un peu comme le crayon avec lequel on dessine l'apparence du site. Twig est implanté directement avec Symfony. Il m'a permis de créer des modèles pour afficher le contenu de manière claire et esthétique, comme organiser les pièces d'un puzzle pour qu'elles s'emboîtent correctement.

J'ai utilisé React.js pour créer des élémént intéractifs et dynamique pour le système de filte et le système de notation par étoiles, offrant ainsi une expérience utilisateur fluide et agréable, tout en permettant aux utilisateurs de filtrer les résultats et de donner leur avis de manière simple et intuitive.

Pour le développement des fonctionnalités, nous pouvons le comparer à l'assemblage des différentes parties d'un puzzle. Chaque fondtionnalité est comme une pièce de puzzle, et mon travail consiste à les assembler pour que le site fonctionne de la manière souhaitée.

J'ai créé une base de données pour manipuler les véhicules d'occasion, les utilisateurs du côtés administrateur (comptes et connexions), les horaires d'ouverture, les avis clients et les services de réparation. La base de données à été créée grâce à l'ORM Doctrine de Symfony. Je vous invite à cliquer sur ce lien pour en savoir plus sur cet outils <a href="https://www.symfony.com/doc/current/doctrine.html">Doctrine ORM.</a>

J'ai développer grâce aux outils de Symfony un système pour contrôler qui peut faire quoi sur le site et créer un tableau de bord adminitrateur, un peu comme une clé qui ouvre différentes portes dans un immeuble. Le patron du garage à une clé spéciale qui lui donne accès à toutes les parties du site, tandis que les employés ont une clé à certaines parties seulement. Cela a été une étape cruciale pour maîtriser la sécurité globale du site.

### Tests et déploiement :

J'ai testé chaque fonctionnalité pour m'assurer qu'elles répondaient aux exigences du cahier des charges. En testant également les performances et la sécurité.

J'ai déployé le site sur une serveur distant en veillant à ce que tout fonctionne correctement en production. j'ai uilisé le serveur FTP BitVise (un serveur ssl) et j'ai hébergé le site sur Plesk. Tous les dossiers et fichiers de mon site ont été transférés de mon ordinateur à un serveur pour que le code soit retranscrit sur l'adresse de l'hébergement.

Un support et une formation à été nécessaire pour que le client puisse utiliser le système, et j'ai assuré un support continu après le déploiement.

#### Durée et temps

- J'ai réalisé ce projet sur une période de deux mois.
- Cette échéance de temps limitée m'a permis de maintenir un rythme de travail efficace et de respecter les détails fixés pour la livraison du projet.

Vous avez besoin d'un site interne pour votre entreprise ?

> Écrivez-moi !
