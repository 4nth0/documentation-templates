Cette page est un exemple de page d'index d'un projet.

Une notice explication est dispobnible ici : [howto.md](./howto.md)

---

# Projet X : Plateforme de Streaming Vidéo

## Entête du Document

| Information                | Description                                                        |
|----------------------------|--------------------------------------------------------------------|
| Fonctionnalités principales | Streaming vidéo, Chat en direct, Abonnements                      |
| Product Owner              | John Doe                                                           |
| Tech Owners                | Jane Smith, Alice Johnson                                          |
| Dépendances                | Base de données des utilisateurs, Service de paiement (Stripe)     |
| Risques Majeurs            | Latence du réseau, Faille de sécurité                              |
| Dépôt                      | [GitHub](https://github.com/exemple/projet-x)                      |
| Observabilité              | [Grafana](#), [Datadog](#)                                         |
| Statut du Projet           | En développement                                                   |
| Version Actuelle           | 1.0.0                                                              |
| Contacts d'Urgence         | John Doe (PO), Jane Smith (Tech)                                   |

## Sommaire

1. [Liste des Tickets](#liste-des-tickets)
2. [Présentation Rapide](#présentation-rapide)
3. [Fonctionnalités](#fonctionnalités)
4. [Risques Majeurs](#risques-majeurs)
5. [Historique](#historique)

---

## Liste des Tickets

* **En cours** : 
    * `VID-234` Implémentation de la fonctionnalité de chat
    * `VID-235` Optimisation de la latence du streaming
* **À venir** : 
    * `VID-236` Refonte de l'interface utilisateur
    * `VID-237` Intégration de la passerelle de paiement

Pour plus d'informations, consultez notre [Jira](#).

---

## Présentation Rapide

Projet X est une plateforme de streaming vidéo qui propose des fonctionnalités de chat en direct et des options d'abonnement.

Le projet utilise React pour le frontend et Node.js pour le backend. Nous utilisons également WebRTC pour le streaming en direct et Stripe pour les paiements.

---

## Fonctionnalités

### Streaming vidéo
Permet aux utilisateurs de regarder des vidéos en haute définition. Prend en charge plusieurs formats de fichier et codecs.

### Chat en direct
Offre une interaction en temps réel entre les utilisateurs pendant le streaming.

### Abonnements
Permet aux utilisateurs de s'abonner à des chaînes premium avec des fonctionnalités exclusives.

---

## Risques Majeurs

- **Latence du réseau** : peut entraîner une mauvaise expérience utilisateur. Voir [Troubleshooting Latency](#).
- **Faille de sécurité** : pourrait compromettre les données des utilisateurs. Voir [Troubleshooting Security](#).

---

## Historique

- **Janvier 2022** : Début du développement
- **Mars 2022** : Lancement de la version alpha, intégration initiale des fonctionnalités de streaming et de chat
- **Juin 2022** : Lancement de la version bêta avec fonctionnalités d'abonnement
- **Septembre 2022** : Version 1.0.0, lancement public

