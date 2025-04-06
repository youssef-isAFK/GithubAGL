# Application de Livraison de Repas

## Membres du groupe

- Amine Barrak  
- Oussema Sammeri  
- Youssef Brahmi  
- Amine Jaziri  

**Date :** 06/04/2025

---

## 1. Sujet du Projet

### Nom du projet :
**Application de Livraison de Repas**

### Description générale :
Ce projet vise à développer une application intuitive permettant aux utilisateurs de commander des repas en ligne. L’application facilitera la mise en relation entre clients, restaurants et livreurs afin d’optimiser l’expérience de commande et de livraison.

### Motivations :
Dans un secteur en pleine expansion, offrir une solution conviviale et efficace représente une formidable opportunité d’innovation. Même si ce choix n’était pas prioritaire, il s’est imposé par la richesse des défis liés à la logistique et à la gestion de l’expérience client.

---

## 2. Spécifications du Projet

### a. Contraintes et Notions de Base

- **Contraintes techniques :**
  - Performance et réactivité (suivi de commande en temps réel)
  - Sécurité des transactions et protection des données personnelles
  - Facilité d’usage pour l’ensemble des acteurs

- **Notions clés :** Convivialité, réactivité, fiabilité

### b. Acteurs

- **Client :** Parcourt le menu, passe commande, suit l’évolution de sa livraison.
- **Restaurant :** Reçoit la commande, prépare les repas et met à jour son statut.
- **Livreur :** Reçoit et confirme l’assignation de livraison, effectue le suivi en temps réel.
- **Administrateur (optionnel) :** Supervise la plateforme et assure un support global.

### c. Fonctionnalités Principales (du point de vue de l’utilisateur)

- **Passer commande :** Sélectionner des plats, personnaliser la commande et procéder au paiement.
- **Suivre la commande :** Visualiser en temps réel l’état de la commande et recevoir des notifications à chaque étape.
- **Gérer les réclamations :** Contacter le support en cas de problème sur la commande ou la livraison.

---

## 3. Diagramme de Cas d’Utilisation


*Une version visuelle sera générée via PlantUML dans le dossier `Diagrammes`.*

---

## 4. Priorisation des Cas d’Utilisation

**Cas d'utilisation à haute priorité pour le 1er sprint :**
1. Passer commande  
2. Suivi de commande  

---

## 5. Spécification Détaillée du Cas d’Utilisation : "Passer Commande"

### a. Description
Ce cas d’utilisation couvre l’ensemble du processus de commande, depuis la sélection des articles jusqu’à la confirmation du paiement.

### b. Préconditions

- L’utilisateur doit être connecté.
- Le panier contient au moins un article.
- Les informations de paiement doivent être valides.

### c. Postconditions

- La commande est enregistrée dans le système.
- Un numéro de commande (identifiant unique) est attribué.
- Un accusé de réception est envoyé à l’utilisateur.

### d. Exemple de Tableau de Décision

| Critère                     | Condition à vérifier                     | Résultat attendu                          |
|----------------------------|------------------------------------------|-------------------------------------------|
| Connectivité de l’utilisateur | Utilisateur connecté                    | Autorisation à passer commande            |
| Validité du panier          | Panier non vide                          | Passage à la validation de la commande    |
| Format des infos utilisateur| Pseudo, nom, prénom, courriel bien formés| Confirmation (accusé et enregistrement)   |

---

## 6. Planification du 1er Sprint

### Objectifs :
- Implémenter les fonctionnalités "Passer commande" et "Suivi de commande".
- Concevoir une interface utilisateur intuitive.
- Mettre en place le système d’enregistrement et de suivi en temps réel.

### Tâches :
- **Interface Utilisateur :** Créer les écrans de sélection des plats, personnalisation, validation.
- **Back-end :** Développement du module de gestion des commandes, intégration du suivi.
- **Tests :** Rédaction des cas de tests (unitaires et de validation) pour vérifier les pré/postconditions.

### Méthodologie :
- Utilisation des outils/commandes du document _Outils & Commandes_.
- Approche agile pour itérations rapides sur les fonctionnalités clés.

---

