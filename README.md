---
title: apparmor ansible role
---
# Apparmor

## Licence

Ce rôle est sous licence XXX

## Avant propos

Ce rôle est conforme au document [GUIDE_HYGIENE_INFORMATIQUE] de l'ANSSI, uniquement si vous utilisez les valeurs par défauts du rôle.

Ce rôle ne garanti pas la conformité en cas de modification de ces valeurs, bien que d'autres valeurs puissent être conformes.

## Description

Ce rôle configure le serveur installe et configure _apparmor_ .
_Apparmor_ est un outils permettant à l'administrateur système d'associer à chaque programme un profil de sécurité qui restreint les capacités de celui-ci.
Ce rôle est configuré pour qu'il soit conforme au [GUIDE_HYGIENE_INFORMATIQUE] de l'ANSSI :fr: :

> https://cyber.gouv.fr/publications/FIXME

---

## Conformité ANSSI APPARMOR

Signification de la couverture :

* :white_check_mark: la recommandation est couverte par ce rôle
* :x: la recommandation n'est pas couverte par ce rôle
* :no_entry_sign: la recommandation ne peut pas être couverte par une solution technique

| Recommandation | Couverture | Configuration | Valeur par défaut | Commentaire |
| ---  | ---                  | ---           | ---    | ---         |
| R1   | :no_entry_sign:      |    		| | |
| R2   | :no_entry_sign:      |    		| | |
| R3   | :no_entry_sign:      |    		| | |
| R4   | :no_entry_sign:      |    		| | |
| R5   | :no_entry_sign:      |    		| | |
| R6   | :no_entry_sign:      |    		| | |
| R7   | :no_entry_sign:      |    		| | |
| R8   | :no_entry_sign:      |    		| | |
| R9   | :white_check_mark:   |    		| | |
| R10  | :x:                  |    		| | |
| R11  | :x:                  |    		| | |
| R12  | :x:                  |    		| | |
| R13  | :x:                  |    		| | |
| R14  | :x:                  |    		| | |
| R15  | :x:                  |    		| | |
| R16  | :x:                  |    		| | |
| R17  | :x:                  |    		| | |
| R18  | :x:                  |    		| | |
| R19  | :x:                  |    		| | |
| R20  | :x:                  |    		| | |
| R21  | :x:                  |    		| | |
| R22  | :x:                  |    		| | |
| R23  | :x:                  |    		| | |
| R24  | :x:                  |    		| | |
| R25  | :x:                  |    		| | |
| R26  | :no_entry_sign:      |    		| | |
| R27  | :x:                  |    		| | |
| R28  | :x:                  |    		| | |
| R29  | :white_check_mark:   |    		| | |
| R30  | :no_entry_sign:      |    		| | |
| R31  | :x:                  |    		| | |
| R32  | :x:                  |    		| | |
| R33  | :x:                  |          | | |
| R34  | :no_entry_sign:      |          | | |
| R35  | :no_entry_sign:      |          | | |
| R36  | :x:                  |          | | |
| R37  | :no_entry_sign:      |          | | |
| R38  | :no_entry_sign:      |          | | |
| R39  | :no_entry_sign:      |          | | |
| R40  | :no_entry_sign:      |          | | |
| R41  | :no_entry_sign:      |          | | |
| R42  | :no_entry_sign:      |          | | |