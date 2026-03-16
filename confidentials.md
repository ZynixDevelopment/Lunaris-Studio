# Politique de Confidentialité — Lunaris Studio Bot

> **Dernière mise à jour :** 16 mars 2026
> **Version :** 1.0.0

---

## 1. Introduction

**Lunaris Studio** (ci-après « nous », « notre » ou « Lunaris Studio ») s'engage à protéger la vie privée des utilisateurs de **Lunaris Bot** (ci-après « le Bot »).

La présente Politique de Confidentialité décrit quelles données sont collectées, pourquoi elles le sont, comment elles sont utilisées, stockées et protégées, ainsi que les droits dont vous disposez à leur égard.

En utilisant le Bot, vous reconnaissez avoir lu et compris cette politique.

---

## 2. Responsable du traitement des données

| Champ | Information |
|---|---|
| **Entité** | Lunaris Studio |
| **Contact** | contact@lunaris-studio.dev *(à remplacer)* |
| **GitHub** | [github.com/lunaris-studio](https://github.com/lunaris-studio) |
| **Discord** | Serveur officiel Lunaris Studio |

---

## 3. Données collectées

Le Bot collecte uniquement les données **strictement nécessaires** à son fonctionnement. Aucune donnée sensible (mot de passe, numéro de téléphone, données bancaires, etc.) n'est jamais collectée.

### 3.1 Données collectées automatiquement

| Donnée | Type | Finalité |
|---|---|---|
| ID utilisateur Discord | Identifiant numérique | Gestion des tickets, avertissements, rôles |
| ID de serveur (guild) | Identifiant numérique | Configuration par serveur |
| ID de canal (channel) | Identifiant numérique | Configuration des logs, tickets, panneaux |
| ID de rôle | Identifiant numérique | Gestion des rôles automatiques et panneaux |
| Horodatage des actions | Date et heure | Journaux d'activité et modération |

### 3.2 Données collectées via les fonctionnalités

| Fonctionnalité | Données collectées |
|---|---|
| **Tickets** | ID utilisateur, type de ticket, statut, transcription des messages, date d'ouverture/fermeture |
| **Modération** | ID utilisateur ciblé, ID du modérateur, raison de l'action, date |
| **Avertissements** | ID utilisateur, ID du modérateur, raison, date |
| **Panneaux de rôles** | ID de rôles configurés, ID du panneau, ID du message |
| **Configuration serveur** | Paramètres de canaux et rôles définis par les administrateurs |

### 3.3 Données NON collectées

Nous ne collectons **jamais** :

- Le contenu de vos messages en dehors des tickets ouverts
- Votre adresse email, numéro de téléphone ou toute information personnelle hors Discord
- Votre adresse IP
- Des données de navigation ou de localisation
- Des informations financières ou bancaires
- Le contenu de vos messages privés (DM)

---

## 4. Base légale du traitement

Conformément au **Règlement Général sur la Protection des Données (RGPD — UE 2016/679)**, le traitement de vos données repose sur les bases légales suivantes :

| Base légale | Application |
|---|---|
| **Intérêt légitime** | Fonctionnement technique du Bot, modération du serveur |
| **Consentement** | Utilisation volontaire des fonctionnalités (tickets, rôles) |
| **Obligation légale** | Conservation de journaux en cas de signalement d'activité illégale |

---

## 5. Utilisation des données

Les données collectées sont utilisées **exclusivement** pour :

- ✅ Faire fonctionner les fonctionnalités du Bot (tickets, modération, rôles, logs)
- ✅ Permettre aux administrateurs de modérer leur serveur
- ✅ Sauvegarder les transcriptions de tickets à des fins de support
- ✅ Maintenir l'historique des sanctions de modération
- ✅ Configurer le Bot selon les préférences de chaque serveur
- ✅ Améliorer la stabilité et corriger les bugs

Les données ne sont **jamais** utilisées pour :

- ❌ De la publicité ou du marketing
- ❌ De la vente ou de la location à des tiers
- ❌ Du profilage ou de la surveillance d'utilisateurs
- ❌ Des analyses commerciales ou statistiques publiques

---

## 6. Stockage et sécurité des données

### 6.1 Stockage

Les données sont stockées dans une base de données **SQLite locale** sur le serveur hébergeant le Bot. Elles ne sont pas transmises à des services cloud tiers à des fins de stockage.

### 6.2 Durée de conservation

| Type de donnée | Durée de conservation |
|---|---|
| Configuration serveur | Tant que le Bot est présent sur le serveur |
| Tickets et transcriptions | Tant que le Bot est présent sur le serveur |
| Avertissements de modération | Tant que le Bot est présent sur le serveur |
| Journaux d'événements | Non persistants — affichés en temps réel uniquement |

Lorsque le Bot est retiré d'un serveur, les données associées à ce serveur peuvent être supprimées sur demande (voir section 8).

### 6.3 Sécurité

Nous mettons en œuvre les mesures de sécurité suivantes :

- Accès à la base de données limité au processus du Bot uniquement
- Token du Bot stocké dans des variables d'environnement, jamais en dur dans le code
- Aucune interface web ou API publique exposant les données
- Mises à jour régulières des dépendances pour corriger les vulnérabilités connues

Cependant, aucun système n'est infaillible. En cas de violation de données, nous nous engageons à en informer les parties concernées dans les meilleurs délais.

---

## 7. Partage des données avec des tiers

Lunaris Studio **ne vend, ne loue et ne partage pas** vos données personnelles avec des tiers, à l'exception des cas suivants :

| Tiers | Raison | Données transmises |
|---|---|---|
| **Discord Inc.** | Fonctionnement inhérent à la plateforme Discord | IDs, actions via l'API Discord |
| **Autorités légales** | Obligation légale suite à une réquisition judiciaire | Données requises par la loi |

Discord Inc. dispose de sa propre politique de confidentialité consultable sur [discord.com/privacy](https://discord.com/privacy).

---

## 8. Vos droits (RGPD)

En tant que résident de l'Union Européenne, vous disposez des droits suivants sur vos données personnelles :

### 8.1 Droit d'accès
Vous pouvez demander à consulter toutes les données que nous détenons vous concernant.

### 8.2 Droit de rectification
Vous pouvez demander la correction de données inexactes ou incomplètes.

### 8.3 Droit à l'effacement (« droit à l'oubli »)
Vous pouvez demander la suppression de vos données personnelles, sous réserve des obligations légales de conservation.

### 8.4 Droit à la limitation du traitement
Vous pouvez demander la suspension temporaire du traitement de vos données dans certains cas.

### 8.5 Droit à la portabilité
Vous pouvez demander à recevoir vos données dans un format structuré et lisible par machine.

### 8.6 Droit d'opposition
Vous pouvez vous opposer au traitement de vos données basé sur l'intérêt légitime.

### 8.7 Comment exercer vos droits

Pour exercer l'un de ces droits, contactez-nous via :
- **Email :** contact@lunaris-studio.dev *(à remplacer)*
- **Discord :** Serveur officiel Lunaris Studio — ouvrez un ticket

Nous nous engageons à répondre à toute demande dans un délai de **30 jours**.

---

## 9. Cookies et technologies de suivi

Le Bot Discord n'utilise **aucun cookie**, pixel de suivi, ou technologie de surveillance similaire. Il s'agit d'une application backend qui interagit uniquement via l'API Discord.

---

## 10. Mineurs

Le Bot n'est pas destiné aux personnes de moins de **13 ans**, conformément aux Conditions d'Utilisation de Discord. Nous ne collectons pas sciemment de données concernant des mineurs de moins de 13 ans.

Si vous êtes parent ou tuteur et pensez que votre enfant nous a fourni des données personnelles, contactez-nous immédiatement afin que nous procédions à leur suppression.

---

## 11. Modifications de cette politique

Lunaris Studio se réserve le droit de mettre à jour cette Politique de Confidentialité à tout moment. Les modifications sont effectives dès leur publication sur ce dépôt GitHub.

La date de **« Dernière mise à jour »** en haut de ce document sera systématiquement actualisée. Nous vous encourageons à consulter régulièrement cette page.

La poursuite de l'utilisation du Bot après modification vaut acceptation de la nouvelle politique.

---

## 12. Réclamations

Si vous estimez que le traitement de vos données ne respecte pas la réglementation applicable, vous avez le droit d'introduire une réclamation auprès de l'autorité de contrôle compétente.

**En Belgique :**
> **Autorité de Protection des Données (APD)**
> Rue de la Presse 35, 1000 Bruxelles
> 🌐 [www.autoriteprotectiondonnees.be](https://www.autoriteprotectiondonnees.be)
> 📧 contact@apd-gba.be

---

## 13. Contact

Pour toute question relative à cette Politique de Confidentialité :

- **Email :** contact@lunaris-studio.dev *(à remplacer par ton vrai email)*
- **Discord :** Serveur officiel Lunaris Studio
- **GitHub :** [github.com/lunaris-studio](https://github.com/lunaris-studio)

---

*© 2026 Lunaris Studio — Tous droits réservés.*
