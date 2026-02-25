# Timelendar

Application de calendrier collaboratif desktop (projet privé). **Aucune installation** : le logiciel fonctionne seul, prêt à l’emploi.  
*[English](README.en.md)*

## Éditions : Free et Pro

Timelendar est proposé en **deux éditions** :


|                                       | **Free** | **Pro (payante)** |
| ------------------------------------- | -------- | ----------------- |
| Calendrier & timeline                 | ✅        | ✅                 |
| Événements locaux, todo, sauvegardes  | ✅        | ✅                 |
| Compte utilisateur (Supabase)         | ❌        | ✅                 |
| Workspaces partagés & synchronisation | ❌        | ✅                 |
| Connexion CalDAV / iCloud / Outlook   | ❌        | ✅                 |
| Onglet Données (export, etc.)         | ❌        | ✅                 |
| Titre animé (marque Pro)              | ❌        | ✅                 |


**Version gratuite (Free)** : usage local, sans compte. Données sur votre machine.

**Version payante (Pro)** : compte, calendriers partagés, sync temps réel, CalDAV/iCloud et **synchronisation des calendriers Outlook**. **La version Pro sera disponible sous peu** ; vous pouvez tester la version Free en attendant.

Lors d’un **abonnement**, un lien pour télécharger la version Pro vous sera fourni.

### Build des éditions

```bash
npm run tauri:build:free   # Free
npm run tauri:build:full   # Pro
```

---

## Fonctionnalités

- 📅 **Calendrier** : vues mois, semaine et année ; création et édition d’événements
- 📊 **Timeline** : blocs et lignes par semaine, onglets multiples, glisser-déposer, redimensionnement
- ✏️ **Événements** : récurrence (quotidien à annuel), édition rapide, envoi calendrier ↔ timeline
- 📌 **Deadlines** : dates d’échéance visibles sur la timeline et dans les événements
- 📋 **Liste de tâches (todo)** intégrée dans le header
- 💾 **Sauvegarde et restauration** : export/import de backup (fichier .json) par workspace
- 🎨 **Grande versatilité des couleurs** : palettes (Classique, Duo, Timelendar…), mode clair/sombre, couleurs par calendrier
- 👥 **Pro** : workspaces partagés, sync temps réel, invitations et rôles (owner, admin, member, viewer), CalDAV/iCloud et **calendriers Outlook**
- 📡 **Mode hors ligne** : utilisation sans connexion ; sync à la reconnexion (Pro)
- 🌐 **Bilingue** : français et anglais
- 🖥️ Application desktop native (Windows + macOS)

---

## Signature et avertissements de sécurité (Windows / Mac)

L’application **n’est pas signée** : nous n’avons pas de certificat de signature de code (licence payante). Sous **Windows** et **macOS**, l’antivirus ou le système peut donc afficher un avertissement de sécurité au premier lancement.

**Ce n’est pas dangereux.** Le logiciel est sain ; il n’est simplement pas encore assez rentable pour justifier le coût d’une licence de signature. Nous préférons rester transparents sur ce point.

Pour savoir **comment contourner** cet avertissement et installer/lancer l’app en toute confiance, reportez-vous au fichier **README.txt** fourni avec l’application ou dans le dépôt.

Projet privé – tous droits réservés.  
