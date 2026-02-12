# Labs & Challenges – Digital Forensics Practice

Cette section présente les laboratoires pratiques réalisés afin d’appliquer les concepts de criminalistique numérique étudiés dans le projet.

---

## Room : TryHackMe – Intro to Digital Forensics

🔗 [https://tryhackme.com/room/introdigitalforensics](https://tryhackme.com/room/introdigitalforensics)

### Objectif

Comprendre les bases de la criminalistique numérique et le processus d’investigation.

### Compétences acquises

* Compréhension du rôle du forensic dans les enquêtes
* Chaîne de possession (Chain of Custody)
* Acquisition et préservation des preuves
* Analyse des métadonnées

### Analyse réalisée

* Extraction de métadonnées d’un document PDF
* Analyse EXIF d’images
* Identification de l’auteur et de la date de création
* Localisation géographique via coordonnées GPS

### Outils utilisés

* `pdfinfo`
* `exiftool`

### Ce que j’ai appris

Cette room m’a permis de comprendre comment les enquêteurs reconstruisent un incident à partir d’informations cachées dans les fichiers, notamment les métadonnées laissées par les utilisateurs et les appareils.

---

## Room : Disk Analysis & Autopsy

🔗 [https://tryhackme.com/room/autopsy2ze0](https://tryhackme.com/room/autopsy2ze0)

### Objectif

Réaliser une investigation complète sur une image disque Windows.

### Compétences acquises

* Analyse d’image disque
* Recherche d’artefacts système
* Identification d’activités suspectes
* Reconstitution d’actions utilisateur

### Analyse réalisée

* Identification des comptes utilisateurs
* Recherche d’outils malveillants
* Analyse des connexions réseau
* Investigation des fichiers supprimés
* Analyse de scripts PowerShell suspects

### Outils utilisés

* Autopsy
* Analyse manuelle d’artefacts Windows

### Ce que j’ai appris

Cette investigation m’a appris à analyser un système compromis, corréler plusieurs traces numériques et comprendre le comportement d’un attaquant après compromission.

---

## Conclusion

Ces laboratoires m’ont permis de passer de la théorie à la pratique en appliquant une méthodologie d’investigation réelle, similaire à celle utilisée dans les équipes SOC et DFIR.
