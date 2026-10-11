## Plume 0.1.50

### Des corrections qui utilisent mieux la phrase

- « Je mapele » et « Je mapel » deviennent **« Je m'appelle »**.
- Plume adapte la forme au sujet: **« tu m'appelles »**, **« ils m'appellent »**.
- Après un verbe comme devoir: « Il doit mapele » devient **« Il doit m'appeler »**.
- Les pronoms **m’**, **t’** et **s’** sont examinés avant le choix d'un mot ressemblant, pour éviter de perdre l'apostrophe et le pronom.
- **a / à** mieux reconnus dans « à mon goût », « à mon avis », « arrivé à 13 h 47 » et « envoyé ce mail à Paul ».
- « Il m'appelle demain » garde **demain** en minuscule.

Cette version inclut aussi le dictionnaire enrichi, l'analyseur de phrase et
le modèle local Context 1.4 ajoutés depuis la dernière publication.
Tes mots protégés, abréviations, apprentissages et réglages sont conservés.
La correction fonctionne sur ton PC.

### Télécharger et lancer

Télécharge **Plume-windows-x64.zip**, décompresse-le entièrement, puis ouvre
**Plume.exe**. Garde le dossier **_internal** à côté de l'application.
Si tu utilises déjà Plume, la nouvelle version est proposée par sa recherche
de mises à jour, automatiquement au démarrage si l'option est activée.

### Vérifications et limites

- 105 cas ciblés réussis et 52 essais de frappe simulée réussis.
- Aucune nouvelle régression sur un ancien bilan grammatical de 504 phrases.
- Ces bilans sont limités: Plume doit encore progresser sur les phrases ambiguës et complexes.
- Les poids du modèle Context 1.4 restent inchangés dans ce correctif; les améliorations portent sur les décisions du moteur.

Le rapport détaillé est fourni dans `_internal/models/plume_moteur_0150_evaluation.json`.

**Windows 64 bits · Gratuit · Correction locale**
