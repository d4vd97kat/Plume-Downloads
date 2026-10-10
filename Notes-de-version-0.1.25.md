## Plume 0.1.25

Cette version améliore les participes passés simples, les apostrophes, la reconnaissance des villes et la ponctuation pendant la frappe.

### Corrections enrichies

- Avec **Accords et conjugaisons** activé, « j'ai mange » peut devenir « j'ai mangé ». Le moteur utilise le verbe connu après l'auxiliaire, sans accentuer tous les mots terminés par `e`.
- « Jecris » retrouve le sujet et l'apostrophe : « J'écris ». Les premières personnes reconnues passent avant la recherche de lettres superflues.
- Le groupe auxiliaire + participe permet de reconnaître la préposition dans « j'ai mangé a… » → « j'ai mangé à… ».
- Les activités localisées, comme manger, travailler ou étudier, aident à distinguer « à Paris » du nom commun dans « des paris ».
- Les corrections du contexte, des noms et de la ponctuation sont regroupées : « J'ai mangé a paris.Ce matin » → « J'ai mangé à Paris. Ce matin ».
- La réparation des espaces après la ponctuation est plus réactive après le relâchement des touches. Les contrôles du champ de saisie et les exclusions des adresses, nombres et expressions protégées restent actifs.

### Réglages et limites

Tes mots protégés, abréviations et choix personnels restent prioritaires. Les données personnelles restent sur le PC.

La compilation, le démarrage local et 22 vérifications ciblées du moteur ont été contrôlés. Le comportement pendant la frappe réelle reste à confirmer dans les applications utilisées. Les phrases complexes, les accords des participes avec un complément placé avant et les verbes pronominaux ne sont pas entièrement couverts.

### Mise à jour et installation

Depuis une version compatible, ouvre **Options**, clique sur **Vérifier**, puis sur **Installer**. Aucun compte GitHub n'est nécessaire.

Pour une installation manuelle, télécharge **Plume-windows-x64.zip**, décompresse toute l'archive et lance **Plume.exe**. Garde le dossier **_internal** à côté de l'exécutable. Ferme l'ancienne instance avant de remplacer manuellement ses fichiers.
