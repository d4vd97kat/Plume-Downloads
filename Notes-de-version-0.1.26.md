## Plume 0.1.26

Cette version corrige le démarrage de l'installateur et rend les nouvelles versions visibles dans l'interface principale.

### Mises à jour

- Une annonce « Nouvelle version » apparaît dans le bandeau principal, quel que soit l'onglet ouvert, avec un bouton **Mettre à jour**. La page conserve ses dimensions.
- Le téléchargement affiche sa progression et laisse l'interface disponible.
- L'erreur de syntaxe qui empêchait l'ancien installateur PowerShell de démarrer est corrigée.
- Plume attend maintenant la confirmation de préparation du paquet avant de se fermer. Si le téléchargement, la vérification ou la préparation échoue, l'application reste ouverte et explique l'échec.
- L'installateur vérifie l'empreinte et la version, attend l'arrêt des processus de cette installation, conserve l'ancienne version, puis relance le moteur et l'interface. Une erreur après remplacement déclenche une restauration.
- Les préférences, les mots personnels et les abréviations sont conservés, ainsi que l'état actif ou en pause. Le résultat de l'installation est affiché à la réouverture.

### IMPORTANT : recevoir ce correctif depuis une ancienne version

Les versions **0.1.25 et antérieures** possèdent déjà l'ancien installateur défectueux. Elles nécessitent donc **une mise à jour manuelle** pour recevoir son remplacement :

1. Télécharge **Plume-windows-x64.zip**.
2. Quitte Plume depuis son icône près de l'horloge.
3. Décompresse entièrement le ZIP.
4. Remplace ensemble **Plume.exe** et le dossier **_internal** dans le dossier où tu utilises Plume.
5. Relance **Plume.exe**. L'onglet Options doit indiquer **0.1.26**.

Les données personnelles sont dans un dossier séparé et ne sont pas effacées par ce remplacement. Aucun compte GitHub n'est nécessaire pour télécharger le paquet.

### Contrôles effectués

La syntaxe Python et PowerShell, la compilation locale, le contenu du paquet et le redémarrage local ont été contrôlés. Aucun essai complet du nouvel installateur sur les autres PC n'a été effectué pour cette publication ; son comportement reste à confirmer à l'utilisation.
