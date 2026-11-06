# Politique de mots de passe de l'agence

Référence : ANSSI, *Recommandations relatives à l'authentification multifacteur et aux mots de passe*, ANSSI-PG-078, v2.0, 08/10/2021.

## Objectif
Protéger les accès partagés de l'agence (portails d'annonces, banque, paie, CRM) en rangeant tous les mots de passe dans un coffre unique et en fixant des règles communes. La politique est adaptée au contexte de l'agence (9 personnes, données clients). (R20, p. 27 ; R3, p. 18)

## Longueur minimale
Le mot de passe maître du coffre, seul à mémoriser, est une phrase de passe d'au moins 15 caractères, soit le niveau « fort à très fort » du guide. Les mots de passe des services sont générés par le coffre et dépassent 20 caractères. Aucune longueur maximale n'est imposée, pour permettre les phrases de passe. (R21 et tableau 3, p. 28 ; R22, p. 29)

## Un mot de passe par service
Chaque portail ou outil a son propre mot de passe, généré par le coffre : si l'un fuit, un seul service est touché. Les mots de passe par défaut sont changés dès l'installation. (R33, p. 35 ; R38, p. 36)

## Usage obligatoire du coffre
Tous les accès de l'agence sont stockés dans le coffre Vaultwarden, dans la collection correspondant au rôle. Les cahiers, SMS, fichiers bureautiques et e-mails ne servent plus à conserver ou transmettre un mot de passe. (R31, p. 34 ; R34 et R35, p. 35)

## Double authentification
Le compte de la directrice, qui voit toutes les collections, est protégé par un second facteur de type code TOTP généré par une application. Le SMS n'est pas utilisé comme moyen de réception d'un facteur. (R1, p. 14 ; R8, p. 21 ; TOTP cité en section 2.5, p. 16)

## Départ d'un salarié
Le jour du départ, la directrice retire le compte de l'organisation, puis change tous les mots de passe des accès que la personne pouvait voir, selon la procédure de départ de l'agence. Le délai est fixé par l'agence selon son analyse de risque. (R18, p. 24 ; R19, p. 25)

## Fuite constatée
En cas de fuite avérée ou suspectée (par exemple un résultat positif sur Have I Been Pwned), les mots de passe concernés sont renouvelés immédiatement, de l'ordre de la journée. Au-delà, les comptes sont désactivés jusqu'à réactivation par la directrice. (R26, p. 31)