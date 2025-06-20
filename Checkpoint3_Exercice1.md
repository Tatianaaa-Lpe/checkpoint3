 Partie 2 : Configuration de SSH# Partie 1 : Gestion des utilisateurs


**Q.1.1.1 Créer l'utilisateur Lionel Lemarchand avec les même attribut de société que Kelly Rhameur.**

- Faire une copy de l'utilisateur Kelly Rameur et changer le nom pour Lionel Lemarchand afin qu'il ait les mêmes attributs.
- ![image](Images_Ex1/Création_du_compte_Lionel.png)

**Q.1.1.2 Créer une OU DeactivatedUsers et déplace le compte désactivé de Kelly Rhameur dedans.**

- ![image](Images_Ex1/DesactivedUsers.png)
- ![image](Images_Ex1/Désactivation_Compte_User.png)

**Q.1.1.3 Modifier le groupe de l'OU dans laquelle était Kelly Rhameur en conséquence.**

- ![image](Images_Ex1/OU.png)

**Q.1.1.4 Créer le dossier Individuel du nouvel utilisateur et archive celui de Kelly Rhameur en le suffixant par -ARCHIVE.**

- ![image](Images_Ex1/Création_Et_Archive.png)


# Partie 2 : Restriction utilisateurs

**Q.1.2.1 Faire en sorte que l'utilisateur Gabriel Ghul ne puisse se connecter que du lundi au vendredi, de 7h à 17h.**

- ![image](Images_Ex1/Restriction_Horaires_Gabriel.png)

**Q.1.2.2 De même, bloquer sa connexion au seul ordinateur CLIENT01.**

- ![image](Images_Ex1/Restriction_Client01.png)

**Q.1.2.3 Mettre en place une stratégie de mot de passe pour durcir les comptes des utilisateurs de l'OU LabUsers.**

- ![image](Images_Ex1/MDP.png)
- ![image](Images_Ex1/Link_OU.png)

# Partie 3 : Lecteurs réseaux

**Q.1.3.1 Créer une GPO Drive-Mount qui monte les lecteurs E: et F: sur les clients.**

-![image](Images_Ex1/Disques.png)
