# Serveur SMB — Partage de fichiers Linux (Samba)

Mise en place d'un serveur de fichiers sous **Linux** utilisant le protocole **SMB** (Server Message Block) via Samba.

![Configuration accès](https://github.com/user-attachments/assets/555fb69d-3a4f-480a-8de6-b6167d041363)

![Serveur Samba actif](https://github.com/user-attachments/assets/af1d5742-131c-40ce-afa3-e88a85d4617c)

## Description

Ce projet documente la configuration d'un serveur de partage de fichiers réseau (NAS simplifié) avec Samba sur Linux, sécurisé par le pare-feu UFW.

## Technologies utilisées

- **Système** : Linux (Debian/Ubuntu)
- **Service** : Samba (smbd / nmbd)
- **Protocole** : SMB / CIFS (compatible Windows, Linux, macOS)
- **Sécurité** : UFW (pare-feu), authentification utilisateur Samba

## Ce qui a été mis en place

- Installation de Samba (`apt install samba`)
- Création de partages réseau avec droits en lecture/écriture
- Gestion des utilisateurs Samba
- Sécurisation avec UFW (port 445, 139)
- Accès au partage depuis un poste Windows et Linux

## Compétences démontrées

Administration système Linux, réseaux locaux, protocoles de partage de fichiers, sécurité réseau.

