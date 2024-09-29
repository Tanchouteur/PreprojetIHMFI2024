Modification de Admin 

# Menu Administrateur

- **Accueil**
  - Accès à la page d'accueil de l'application.

- **Gérer Profils Type**
  - Créer, modifier ou supprimer des profils type pour les applications.

- **Gérer Droits d’Accès**
  - Consulter et modifier les droits d'accès des employés.
  - Révoquer des droits si nécessaire.

- **Consulter Applications**
  - Voir la liste de toutes les applications disponibles.

- **Notifier Employés**
  - Envoyer des notifications aux employés concernant l'attribution de droits.

- **Rapports**
  - Générer des rapports sur les droits d'accès et les profils type.

- **Paramètres**
  - Gérer les paramètres de l'application.

- **Aide et Support**
  - Accéder à l'aide et aux ressources de support.

- **Déconnexion**
  - Se déconnecter de l'application.

# Tableau des Droits d'Accès

| Droit                                         | Employé                  | Manager                          | Administrateur                     | Date de révocation                      |
|-----------------------------------------------|--------------------------|----------------------------------|------------------------------------|------------------------------------------|
| Accès à une application                       | Oui                      | Oui                              | Oui                                | Date configurable ou vide                |
| Lire les accès dont il dispose                | Oui                      | Oui                              | Oui                                | Vide                                     |
| Demander plus ou moins de droits              | Oui                      | Peut accorder ou refuser         | Non         | Date configurable (selon la demande)     |
| Expliquer sa demande d'augmentation de droits | Oui                      | Oui                              | Non                              | Date configurable                        |
| Octroyer un profil type à un employé         | Non                      | Oui                              | Oui                                | Date configurable                        |
| Gérer et éditer les profils types             | Non                      | Non                              | Oui                                | Vide                                     |
| Demander des ajustements de droits            | Oui                      | Oui                              | Non                               | Date configurable                        |
| Révoquer les droits d’un employé              | Non                      | Oui                              | Oui                                | Date configurable                        |
| Sauvegarder et définir des profils-types      | Non                      | Non                              | Oui                                | Vide                                     |
| Consulter la liste des applications           | Oui (uniquement accessibles) | Oui                           | Oui (toutes)                       | Vide                                     |
| Notifier les employés sur l’attribution de droits | Non                  | Oui                              | Oui                                | Date configurable                        |


# Gérer Profils Type

## Créer Profil Type
Définir un nouveau profil type pour une application spécifique, en spécifiant les droits d'accès associés.

## Modifier Profil Type
Changer les droits d'accès d'un profil type existant pour l'adapter aux besoins de l'entreprise.

## Supprimer Profil Type
Retirer un profil type qui n'est plus nécessaire ou pertinent pour l'application.

## Consulter Profils Types
Afficher la liste des profils types existants pour chaque application, avec les droits d'accès associés.

# Créer Profil Type

## Formulaire de Création de Profil Type

**Nom du Profil Type:**  
[Champ de texte] (Ex: "Profil Manager", "Profil Employé")

**Application Associée:**  
[Liste déroulante] (Sélectionner l'application pour laquelle ce profil est défini)

**Droits d'Accès:**  
- Accès à l'Application: [Checkbox] (Oui/Non)  
- Lire les Accès: [Checkbox] (Oui/Non)  
- Demander Ajustements de Droits: [Checkbox] (Oui/Non)  
- Gérer Profils Type: [Checkbox] (Oui/Non)  
- Révoquer Droits: [Checkbox] (Oui/Non)  
- Notifier Employés: [Checkbox] (Oui/Non)  
- (Inclure d'autres droits pertinents en fonction des besoins de l'application)

Menu deroulant avec possibilité de cocher 

**Description du Profil:**  
[Zone de texte] (Expliquer brièvement le rôle et l'utilisation du profil)

**Date de Révocation Automatique :**  
[Champ de date] (Spécifier une date à laquelle ce profil sera automatiquement révoqué, si applicable)

[Bouton] "Créer Profil Type"

# Modifier Profil Type

## Formulaire de Modification de Profil Type

**Sélectionner le Profil Type à Modifier:**  
[Liste déroulante] (Sélectionner le profil type à modifier)

**Nom du Profil Type:**  
[Champ de texte] (Ex: "Profil Manager", "Profil Employé")

**Application Associée:**  
[Liste déroulante] (Sélectionner l'application pour laquelle ce profil est défini)

**Droits d'Accès:**  
- Accès à l'Application: [Checkbox] (Oui/Non)  
- Lire les Accès: [Checkbox] (Oui/Non)  
- Demander Ajustements de Droits: [Checkbox] (Oui/Non)  
- Gérer Profils Type: [Checkbox] (Oui/Non)  
- Révoquer Droits: [Checkbox] (Oui/Non)  
- Notifier Employés: [Checkbox] (Oui/Non)  
- (Inclure d'autres droits pertinents en fonction des besoins de l'application)

**Description du Profil:**  
[Zone de texte] (Expliquer brièvement le rôle et l'utilisation du profil)

**Date de Révocation Automatique (facultatif):**  
[Champ de date] (Spécifier une date à laquelle ce profil sera automatiquement révoqué, si applicable)

[Bouton] "Modifier Profil Type"








