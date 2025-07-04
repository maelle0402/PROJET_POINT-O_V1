#  README – Gestion Automatisée des Présences

##  Présentation du Projet
Ce projet a pour objectif de remplacer les feuilles de présence papier par une solution **Web/Mobile** moderne et automatisée. Grâce à l’utilisation de **QR codes** ou **NFC**, chaque étudiant peut enregistrer sa présence de manière simple, rapide et sécurisée.

---

##  Fonctionnalités principales
-  Application Web avec interfaces selon le rôle (Étudiant / Enseignant / GRETA / Admin)
-  Pointage automatisé via **QR code**
-  Enregistrement sécurisé des présences en base de données
-  Tableau de bord interactif pour le suivi et l’export
-  Génération de fiches PDF et envoi automatisé vers la scolarité
-  Gestion des droits et accès via rôles utilisateurs

---

## Technologies utilisées
- **Frontend** : HTML / CSS / JavaScript (avec éventuellement un framework comme React)
- **Backend** : Node.js / Express.js
- **Base de données** : SQL Server management
- **QR Code** : Librairie `qrcode` ou équivalent
- **Outils** : VS Code, GitHub, Gamma.app, Postman

---

## Structure du projet
```
/frontend          → Interface utilisateur
/backend           → Serveur, API REST
/database          → Scripts de création de la BDD
/docs              → Documentation technique et utilisateur
/qrcodes           → Dossier contenant les QR Codes générés
/tests             → Tests fonctionnels et unitaires
README.md          → Ce fichier
```


###  Gestion des rôles
- Étudiants : Scanne le QR code
- Enseignants : Validation / supervision
- GRETA : Consultation / export
- Référent numérique : Déploiement et maintenance

---

##  Répartition de l’équipe
| Nom | Rôle |
|-----|------|
| Axel HERMITE | Chef de projet, QR code, suivi, soutenance |
| Noah ANZALA | Analyste / Designer fonctionnel |
| Alex COUTTÉ-PÉROUMAL | Développeur serveur / BDD |
| Charles CABARRUS | Backend / API REST |
| **Maelle JAPPONT** | Frontend / Tests fonctionnels |

---

##  Documents inclus
- Cahier des charges
- Maquettes fonctionnelles
- Documentation technique (API, BDD)
---

##  Livraison finale
- Démo Web
- QR codes générés
- Base de données opérationnelle
- Présentation + Rapport final PDF
