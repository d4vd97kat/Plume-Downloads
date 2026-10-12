## Plume 0.1.56 — Oria progresse

Oria, l'IA locale de Plume, a reçu un nouvel entraînement pour mieux choisir
une correction à partir des mots qui l'entourent. Plume continue de fonctionner
sur ton PC, sans envoyer tes messages sur Internet.

### Les nouveautés depuis la version publique 0.1.50

- **Des accords mieux guidés par la phrase** : Plume examine les sujets,
  les noms, les adjectifs et certains participes avant de choisir une forme.
- **Oria réentraînée** : 339 856 contextes d'apprentissage, issus de français
  courant, soutenu, oral et d'exemples familiers, avec de nouveaux indices grammaticaux.
- **Des corrections plus prudentes** lorsque plusieurs lectures sont possibles,
  notamment pour les homophones, les noms propres et les participes.
- **Un blocage de la correction réparé** : certaines touches multimédias
  signalées actives par Windows pouvaient empêcher toute correction.

Exemples de cas pris en charge :

| Tu écris… | Plume peut écrire… |
| --- | --- |
| `On travail aujourd'hui.` | `On travaille aujourd'hui.` |
| `Les petit oiseaux chantent.` | `Les petits oiseaux chantent.` |
| `Ces vitres semblent vraiment sale.` | `Ces vitres semblent vraiment sales.` |

La correction dépend du contexte. Plume peut encore laisser passer une faute
ou proposer une correction inadaptée.

### Ce que montrent les évaluations

Sur un bilan de **6 078 contextes réservés**, le nouveau réseau choisit une
forme correcte parmi les propositions dans **92,96 %** des cas, contre
**90,95 %** auparavant. Ce résultat mesure le choix entre des formes proposées,
pas la qualité de toutes les corrections automatiques.

Les deux bilans réservés de correction complète restent inchangés. Aucune
nouvelle régression n'a été détectée dans les lots comparés. **Une précision
générale de 99 % n'est pas démontrée.** Le rapport détaillé et les crédits des
données sont fournis avec Plume, dans le dossier `_internal/models`.

### Télécharger ou mettre à jour

Télécharge **Plume-windows-x64.zip**, choisis **Extraire tout**, puis ouvre
**Plume.exe**. Garde le dossier **_internal** à côté de l'application.

Si tu utilises déjà une version avec le programme de mise à jour corrigé,
ouvre Plume et vérifie les mises à jour dans ses réglages. La recherche
automatique peut aussi annoncer la nouvelle version à l'ouverture de l'interface.
Tu choisis quand l'installer.

Tes mots protégés, abréviations, apprentissages et réglages restent dans ton
profil Windows. Cette version n'utilise aucun de tes messages pour entraîner Oria.

**Windows 64 bits · Gratuit · Correction locale**
