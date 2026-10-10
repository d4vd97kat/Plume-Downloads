## Plume 0.1.23

Cette version rassemble les améliorations apportées depuis la version 0.1.12.

### Correction pendant la frappe

- Distinction plus précise entre **a** et **à** devant un horaire : « Ok a 13h47 » et « demain a 13 h 47 » sont désormais couverts par les règles de préposition. Les emplois du verbe avoir restent préservés.
- Un clic ou un changement de fenêtre n'est plus assimilé à un début de phrase. La casse initiale reste intacte si le contexte ne peut pas être confirmé.
- Reconnaissance du verbe dans « j'appui » / « j'appuie » et « j'envoi » / « j'envoie », avec **Accords et conjugaisons** activé. Les noms « un appui » et « un envoi » sont conservés.
- Recherche orthographique enrichie pour les doubles frappes, lettres inversées, touches voisines et lettres superflues, avec abstention lorsque les candidats sont ambigus.
- Vocabulaire courant et tournures familières enrichis ; reprise de la ponctuation et des accords simples après une courte pause.
- Base locale de prénoms, patronymes, villes, pays et marques, avec distinction prudente des noms communs selon le contexte.
- Les barres d'adresse et les contrôles natifs des navigateurs Chromium sont exclus des remplacements automatiques pour éviter les conflits avec leur autocomplétion.

### Réglages et distribution

- Les raccourcis restent personnalisables et les exceptions personnelles prioritaires.
- La compilation GitHub inclut désormais la même base de noms propres et les mêmes ressources que le paquet local.
- Les préférences et mots personnels restent dans le dossier local de Plume sur le PC.

### Installation

Télécharge **Plume-windows-x64.zip**, décompresse complètement l'archive, puis lance **Plume.exe**. Le dossier **_internal** doit rester à côté de l'exécutable. Ferme l'ancienne instance de Plume avant un remplacement manuel.

Depuis une installation compatible, l'onglet **Options** permet de vérifier et d'installer la nouvelle version.

La compilation et le démarrage local ont été contrôlés. Les cas ambigus restent prudents et le comportement pendant la frappe dans chaque application reste à confirmer à l'utilisation.
