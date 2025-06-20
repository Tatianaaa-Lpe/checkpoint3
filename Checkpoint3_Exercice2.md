# Partie 1 : Gestion des utilisateurs

**Q.2.1.1 Sur le serveur, créer un compte pour ton usage personnel.**

- ![image](Images_Ex2/Création_User.png)

**Q.2.1.2 Quelles préconisations proposes-tu concernant ce compte ?**

- Mettre un mot de passe compliqué (caractères spéciaux ..), limiter les droits d'accès aux dossiers, fichiers, paramètres .., verrouillage du compte si non-utilisation, restriction accès internet.

# Partie 2 : Configuration de SSH

**Q.2.2.1 Désactiver complètement l'accès à distance de l'utilisateur root**

- ![image](Images_Ex2/Permission_Root.png)

**Q.2.2.2 Autoriser l'accès à distance à ton compte personnel uniquement.**

- ![image](Images_Ex2/Permission_tatiana.png)

**Q.2.2.3 Mettre en place une authentification par clé valide et désactiver l'authentification par mot de passe**

-  ![image](Images_Ex2/Clef_Et_MDP.png)

# Partie 3 : Analyse du stockage

**Q.2.3.1 Quels sont les systèmes de fichiers actuellement montés ?**

- md0p1 -> /boot
- cp3--vg-root -> /
- cp3--vg-swap_1 -> [swap]

**Q.2.3.2 Quel type de système de stockage ils utilisent ?**

- Disque dur physique
- RAID
- LVM

**Q.2.3.3 Ajouter un nouveau disque de 8,00 Gio au serveur et réparer le volume RAID**

-  ![image](Images_Ex2/RAID1.png)
-  ![image](Images_Ex2/RAID.png)

**Q.2.3.4 Ajouter un nouveau volume logique LVM de 2 Gio qui servira à héberger des sauvegardes. Ce volume doit être monté automatiquement à chaque démarrage dans l'emplacement par défaut : /var/lib/bareos/storage.**

-

**Q.2.3.5 Combien d'espace disponible reste-t-il dans le groupe de volume ?**

-

# Partie 4 : Sauvegardes

**Q.2.4.1 Expliquer succinctement les rôles respectifs des 3 composants bareos installés sur la VM.**

-


# Partie 5 : Filtrage et analyse réseau

**Q.2.5.1 Quelles sont actuellement les règles appliquées sur Netfilter ?**

- Accepte tout le trafic localhost et les connexions déjà établies


**Q.2.5.2 Quels types de communications sont autorisées ?**

- Trafic local et IPv6

**Q.2.5.3 Quels types sont interdit ?**

- counter drop -> bloque tout le reste

**Q.2.5.4 Sur nftables, ajouter les règles nécessaires pour autoriser bareos à communiquer avec les clients bareos potentiellement présents sur l'ensemble des machines du réseau local sur lequel se trouve le serveur.**

-


# Partie 6 : Analyse de logs

**Q.2.6.1 Lister les 10 derniers échecs de connexion ayant eu lieu sur le serveur en indiquant pour chacun :**

- ![image](Images_Ex2/Log.png) 


