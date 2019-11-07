# Remplacement d'une Livebox 5 par un routeur Ubiquiti EdgeRouter 4
## Introduction
L'objectif de cet article est de documenter le remplacement d'une Livebox 5 par un routeur Ubiquiti EdgeRouter 4 et la configuration des services suivants :
- Internet IPV4
- Internet IPV6
- Service TV Streaming (avec le décodeur UHD - DTIW385)
- Service TV VOD (avec le décodeur UHD - DTIW385)

**LIMITATION 1 : Orange ayant fermé l'accès à ses serveur SIP, il n'est à l'heure actuel pas possible d'utiliser la téléphonie illimité sans la Livebox.**

**LIMITATION 2 : Orange propose sur ses offres Up Fibre un débit de 2Gb partagé. L'utilisation de l'ONT externe et du routeur Ubiquiti EdgeRouter 4 limitera votre débit à 1Gb.**

Cette page est basé sur les travaux de reverse engineering du forum https://lafibre.info/ et spécialement sur le travail réalisé par Zoc, Kgersen, Nanostra, C0mm0n et tous les autres ... Merci pour votre aide inestimable.

Par rapport aux tutoriaux présents sur le forum, l'objectif de cette page est de fournir une solution clef en main pour le remplacement d'une Livebox 5 et l'utilisation du décodeur UDH DTIW385. Ce cas n'a pas été encore traité sur le forum et présente une différence dans le traitement de l'option DHCP 125.

## Pré-requis
Le principal problème dans le remplacement de la Livebox 5 est l'intégration par Orange de l'ONT directement dans la Livebox. En effet dans les tutoriaux de remplacement des Livebox 4, l'ONT (qui pouvait être de type SFP ou externe) était conservé car Orange utilise le numéro de série de l'ONT pour vous identifier sur le réseau. **Tout utilisation d'un ONT tiers aura pour effet de rendre impossible votre accès au réseau.** Il existe des recherches pour modifier le numéro de série d'un ONT tiers et le faire authentifier par Orange [TBD : INSERER LIEN FORUM]

La première étape de ce tutorial consiste donc à faire installer par Orange un ONT externe en amont de votre Livebox 5.
Cette possibilité est prévue par Orange (Page X du manuel de la Livebox 5) car dans certains cas il ne sera pas possible d'amener facilement la fibre jusqu'à la Livebox. Pour ma part j'ai demandé le passage d'un technicien dans le cadre d'une "Installation Experte", une fois le technicien chez moi j'ai expliqué ma problématique et le technicien a été très sympa et m'a installé un ONT externe. Cette étape est couteuse (89 euros) et sa réussite est soumise au bon vouloir du technicien.

Une fois l'ONT externe installé, vous pouvez passer à la configuration de votre routeur.

## Configuration Internet IPV4

A ECRIRE

## configuration Internet IPV6

A ECRIRE

## Configuration de la TV

Le décodeur TV livré avec la Livebox 5 est le décodeur UHD (DTIW385).

A ECRIRE
