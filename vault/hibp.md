# Vérification des adresses sur Have I Been Pwned

| Adresse testée | Résultat | Fuites citées | Conséquence |
|---|---|---|---|
| adresse personnelle | aucune fuite (0 data breaches) | aucune | aucun changement imposé ; garder un mot de passe unique par service et le coffre |
| adresse jetable | aucune fuite (0 data breaches) | aucune | aucun changement imposé ; résultat négatif, ne prouve pas l'absence de fuite non connue |
| directrice@agence.lan | aucune fuite (0 data breaches) | aucune | adresse fictive, non inscrite sur de vrais services : aucune fuite possible |
| negociateur@agence.lan | aucune fuite (0 data breaches) | aucune | adresse fictive, non inscrite sur de vrais services : aucune fuite possible |
| adresse inventée | aucune fuite (0 data breaches) | aucune | adresse inexistante : aucune fuite possible |

## Ce que signifie un résultat positif
Si une adresse apparaît dans une fuite, les identifiants de ce service ont été exposés : le mot de passe utilisé sur ce service est à considérer comme connu d'un attaquant. Il faut le changer immédiatement (de l'ordre de la journée, d'après R26 du guide ANSSI-PG-078), puis le changer partout où il a été réutilisé. C'est la raison d'être de R33 : un mot de passe différent par service limite la fuite à un seul service.
Aucune de mes 5 adresses n'a donné de résultat positif : cette explication est donc une règle générale, pas un constat.

## Ce que signifie un résultat négatif
Un résultat négatif ne garantit pas l'absence de fuite : le site n'indexe que les fuites connues et rendues publiques. Une adresse peut avoir été exposée dans une fuite non découverte ou non publiée. Les adresses en .lan n'existent sur aucun vrai service, donc leur résultat négatif est attendu.