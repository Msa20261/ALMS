# Comptes de test UAT (almsUAT)

Contact et utilisateur portail de test à réutiliser pour les campagnes de test en UAT (ex: vue "Mon Parc Actif", flow "XP France - Raise Object Specific Case", règle d'assignation `ExternalCaseFrance`).

> Données fictives, à usage de test uniquement.

## Contact test

| Champ | Valeur |
|---|---|
| Nom | Ludovic Avoyne |
| Id | `0031t000007nqr8AAA` |
| Email | troquerbe@upmind.fr |
| Téléphone | 02 31 06 31 06 |
| Compte | CHU CAEN (`0011t0000045pOGAAY`) |
| Record Type du compte | ALL - Compte Client |
| Lien UAT | https://alms--uat.sandbox.lightning.force.com/lightning/r/Contact/0031t000007nqr8 |

## Utilisateur portail lié

| Champ | Valeur |
|---|---|
| Nom | Ludovic Avoyne |
| Id | `005AU00000b4DpNYAU` |
| Username | troquerbe@upmind.fr2 |
| Email | troquerbe@upmind.fr |
| Profil | External - IngeBioForme |
| Actif | Oui |
| Contact lié | `0031t000007nqr8AAA` (ci-dessus) |

**Utile pour les tests** : ce profil (`External - IngeBioForme`) est l'un des 3 profils qui déclenchent l'application des règles d'assignation (`Assign_Case`) dans le flow "XP France - Raise Object Specific Case" — pratique pour tester le nouveau routage "Réforme Matériel" vers la queue `SAV_Admin`.
