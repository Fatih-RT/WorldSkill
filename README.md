# SAE 501 - Infrastructure Réseau et Services IT pour les WorldSkills

## 📖 Description

Ce projet a été réalisé dans le cadre de la **SAE 501** en **BUT3** et consiste à concevoir et déployer une **infrastructure réseau** et une **infrastructure de services IT** pour l'événement **WorldSkills Lyon 2024**. Le but est d'assurer la connectivité, la sécurité et la disponibilité des services pour l’organisation **WSL2024** et son partenaire **WSFR**.

L'objectif principal est d'implémenter une architecture réseau basée sur **LAN/WAN**, des **services Active Directory**, de la **virtualisation**, du **pare-feu**, du **VPN**, de la **gestion des VLANs** et bien plus.

<p align="center">
  <img src="https://www.worldskills-france.org/app/uploads/2023/04/317329546_514507990716543_5491866302264516748_n.jpg" alt="Logo WorldSkills" width="250">
</p>

---

## 🚀 Objectifs du Projet

- Déployer une **infrastructure réseau sécurisée** (LAN, WAN, VLAN, routage, pare-feu).
- Mettre en place un **Active Directory** avec des **groupes, utilisateurs et permissions**.
- Configurer des **serveurs** (DHCP, DNS, Web, Mail, VPN, etc.).
- Implémenter un **contrôleur de domaine** pour la gestion centralisée.
- Assurer la **sécurité des accès** (SSH, VPN, ACL, Fail2Ban).
- Configurer des **serveurs web et bases de données**.
- Implémenter un **système de sauvegarde et de supervision**.
- Tester et valider le bon fonctionnement des services.

---

## 🏗️ Architecture Technique

### 🔹 Réseau

- Configuration des **Switches Core et Accès** avec **VLANs et VTP**.
- Mise en place du **routage OSPF, iBGP/eBGP et NAT/PAT**.
- Configuration des **pare-feux et ACL** pour sécuriser les flux.
- Déploiement de **VPN** pour accès distant sécurisé.

### 🔹 Serveurs

- **HQINFRASRV** : Serveur DHCP, VPN, stockage (iSCSI, Samba).
- **HQMAILSRV** : Serveur mail sécurisé (SMTP, IMAP, Webmail).
- **HQDCSRV** : Active Directory, DNS, GPO, stockage.
- **HQWEBSRV** : Hébergement web (HTTPS, RDS).
- **HQWLC** : Contrôleur Wi-Fi centralisé.
- **REMFW** : Pare-feu pour site distant.
- **REMDCSRV** : Contrôleur de domaine secondaire.
- **REMINFRASRV** : Services DNS, DHCP, DFS pour site distant.
- **DNSSRV** : Serveur DNS public et autorité de certification.
- **INETSRV** : Serveur web et FTP sécurisé.

---

## 🗺️ Schémas du projet

<p align="center">
  <img src="Woldskill/Physical - Simplified.drawio.png" alt="Schéma Simplifié de la couche physique" width="250">
  <img src="https://www.worldskills-france.org/app/uploads/2023/04/317329546_514507990716543_5491866302264516748_n.jpg" alt="Logo WorldSkills" width="250">
  <img src="https://www.worldskills-france.org/app/uploads/2023/04/317329546_514507990716543_5491866302264516748_n.jpg" alt="Logo WorldSkills" width="250">
  <img src="https://www.worldskills-france.org/app/uploads/2023/04/317329546_514507990716543_5491866302264516748_n.jpg" alt="Logo WorldSkills" width="250">
  <img src="https://www.worldskills-france.org/app/uploads/2023/04/317329546_514507990716543_5491866302264516748_n.jpg" alt="Logo WorldSkills" width="250">
  <img src="https://www.worldskills-france.org/app/uploads/2023/04/317329546_514507990716543_5491866302264516748_n.jpg" alt="Logo WorldSkills" width="250">
</p>

---

## 📢 Contact

📝 Auteur : Fatih KILIC
📧 Contact : [contact@fatih-kilic.fr](mailto:contact@fatih-kilic.fr)  
🌍 Portfolio : [portfolio.fatih-kilic.fr](portfolio.fatih-kilic.fr)
📌 Projet réalisé dans le cadre du **BUT3 - SAE 501**
