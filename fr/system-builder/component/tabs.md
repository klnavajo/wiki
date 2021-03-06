---
title: Tabs
description: 
published: true
date: 2020-09-24T12:02:33.268Z
tags: 
editor: undefined
---

Les Onglets/*Tabs* sont les composants qui permettent de créer des onglets. Un peu comme les *[reapeater](/system-builder/component/repeater)*, ils fonctionnent en trio avec une [table](/system-builder/scripting/tables) et des [vues/*views*](/system-builder/component/view) de types *sub component*. 
Dans le composant *tab* lui même, il y a les champs spéciaux suivants :

# Table
On y renseigne la table dans laquelle les informations sur les onglets seront prises. (Les informations sont le titre de l'onglet, et l'identifiant de leur vue)

# Title
On y renseigne le nom de la colonne de la table qui contient les titre des onglets (qui seront affichés en haut).

# View's ID
On y renseigne le nom de la colonne de la table qui contient les identifiants des vues dans lesqelles se trouvent les onglets.

Ainsi, les onglets sont affichés par le composant *tab*, mais sont créés dans une autre vue. C'est dans cette dernière que vous allez placer les composants de votre onglet.

### Des problèmes ?
*Tab* ne fonctionne pas dans le mode preview, vous devez lancer un "run" de la fiche pour vérifier que vos onglets fonctionnent.
*Tab* ne fonctionne pas si un (ou plusieurs) identifiant de la table ne correspond à aucune vue. Ainsi, l'erreur la plus courante est une faute de frappe dans l'identifiant de la vue. S'il manque une vue, l'effet est le même.
Dans cette situation, il est possible après la création d'une vue de corriger son identifiant.
