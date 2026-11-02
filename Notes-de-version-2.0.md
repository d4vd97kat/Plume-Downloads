# Miekri 2.0

Version officielle **2.0.0**, publiée le 2 novembre 2026. Plume devient Miekri ;
Eira reste l’assistant de relecture local. Les anciens téléchargements sont conservés.

## Depuis la dernière version publique

- Accueil bleu nuit avec disque animé, état de correction visible en petite
  fenêtre et navigation Protection, Réglages et Ajustements.
- Accès Eira sur toute sa carte et disponibilité du modèle affichée séparément
  de la correction locale ; brouillons conservés pendant la navigation.
- Coquilles par lettres oubliées ou ajoutées, apostrophes et a/à améliorés
  dans les constructions reconnues.
- Accords et participes contextuels plus prudents. L’expression
  `Je fais plein de faute d'orthographe` devient
  `Je fais plein de fautes d'orthographe`, en conservant « plein de ».
- Contrôles des propositions d’Eira pour éviter des changements de sens,
  des reformulations et des changements de nombre non justifiés.
- Préservation des mots protégés, abréviations, refus, réglages et annulations.

## Télécharger

- **Plume-windows-x64.zip** : Miekri pour Windows 64 bits. Extraire entièrement
  et garder Plume.exe avec _internal. Les noms techniques historiques restent
  compatibles avec le mécanisme de mise à jour.
- **Miekri-Eira-Installer-windows-x64.zip** : installation optionnelle du modèle
  Eira. Extraire au même endroit, ouvrir Installer-Eira.bat et prévoir environ
  5 Go de téléchargement ainsi qu’au moins 6 Go libres. Les empreintes sont
  vérifiées avant installation. Un pack existant n’est pas écrasé.
- **SHA256SUMS.txt** : sommes de contrôle des deux ZIP.

Les poids Qwen3-8B sont téléchargés depuis leur source officielle figée et ne
sont pas réentraînés pour cette version. Les textes restent sur le PC.

## Vérifications et limites

La publication conserve les contrôles grammaticaux et Windows locaux sur profils
fictifs, les vérifications de l’archive de mise à jour, de l’installateur Eira et
du démarrage compilé. Les 400 phrases de régression connues ne perdent aucune
bonne sortie dans les parcours contrôlés, sans nouvelle génération Qwen.

La grammaire reste partielle. Des noms de sens ambigu et certains adjectifs
homographes sont laissés inchangés ; tous les accords complexes ne sont pas
résolus. Les exemples préparés ne démontrent pas une précision générale.
Les performances du grand modèle dépendent du matériel. La frappe physique,
les lecteurs d’écran et tous les réglages DPI n’ont pas été qualifiés pour
cette publication.
