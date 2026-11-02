# Miekri 2.0 — anciennement Plume

**Un correcteur gratuit pour écrire en français sur Windows, avec Eira pour relire le contexte.**

**[Installer Miekri avec Eira pour Windows](https://github.com/d4vd97kat/Plume-Downloads/releases/latest/download/Installer-Miekri.exe)** ·
[Nouveautés de la 2.0](Notes-de-version-2.0.md) ·
[Une seule installation](#bien-démarrer)

![Accueil de Miekri : fond bleu nuit, disque central, état de correction et accès Protection, Réglages, Ajustements et Eira.](assets/miekri-accueil.png)

*Aperçu sur un profil de démonstration. Les textes personnels n’apparaissent pas dans cette capture.*

## Écrire comme d’habitude

Miekri peut corriger des coquilles, retrouver une apostrophe, choisir certains
homophones et accorder les mots en tenant compte de leur contexte. Termine un
mot par un espace ou une ponctuation et laisse une courte pause pour la relecture.

| Tu écris… | Miekri peut corriger… |
| --- | --- |
| `Je fais plein de faute d'orthographe` | `Je fais plein de fautes d'orthographe` |
| `dvenir` | `devenir` |
| `absollulment` | `absolument` |

Le registre et les formulations sont conservés : « plein de » reste « plein de ».
Un nom comme « courage » n’est pas mis au pluriel simplement parce qu’il suit
une quantité. Les cas non résolus peuvent rester inchangés.

La correction reste imparfaite : elle peut manquer une faute ou se tromper.
Les exemples sont préparés et ne constituent pas un taux général de précision.

## Bien démarrer

1. Télécharge **[Installer-Miekri.exe](https://github.com/d4vd97kat/Plume-Downloads/releases/latest/download/Installer-Miekri.exe)**.
2. Ouvre ce fichier, puis clique sur **Installer Miekri et Eira**.
3. Une fois terminé, clique sur **Ouvrir Miekri**.

L’installateur récupère Miekri et le modèle Eira au même endroit. Tu n’as plus
à télécharger ni à extraire deux archives. Un raccourci peut être ajouté au
Bureau et au menu Démarrer. Aucun compte ni Python à installer.

Le premier téléchargement représente environ **5 Go** : prévois **6 Go libres**
et une connexion Internet. Tu peux arrêter puis relancer l’installateur pour
reprendre. Si Eira est déjà présente et conforme, son modèle est conservé.
Les fichiers sont vérifiés avant installation ; une ancienne version remplacée
est sauvegardée. Si Miekri fonctionne déjà, quitte-le depuis son icône près de
l’horloge avant de remplacer ses fichiers.

Miekri est prévu pour **Windows 64 bits**. Les règles de correction fonctionnent
sans le grand modèle ; l’installation recommandée prépare aussi Eira pour la
relecture. Ses besoins en mémoire et ses performances dépendent du PC.
Le modèle est Qwen3-8B, préentraîné ; son chargement peut prendre un moment.
L’accueil distingue la disponibilité d’Eira de celle du correcteur local.

Tes mots protégés, abréviations et réglages restent personnels. Fermer la fenêtre
peut laisser le correcteur actif près de l’horloge ; son menu permet de le quitter.

### Installation manuelle

Les [archives de la release](https://github.com/d4vd97kat/Plume-Downloads/releases/tag/v2.0.0)
restent disponibles : Plume-windows-x64.zip pour l’application et
Miekri-Eira-Installer-windows-x64.zip pour préparer le modèle séparément.
Leurs noms historiques sont conservés pour les anciennes mises à jour.
L’installateur unique ci-dessus est le parcours recommandé.

## Tes textes restent sur ton PC

Les corrections et la relecture s’effectuent localement. Tes messages ne sont
pas envoyés à un service de correction distant. Internet sert au téléchargement
du logiciel, du modèle et des mises à jour. Aucun de tes messages ne sert à
l’entraînement des modèles fournis.

## Mettre à jour une ancienne version

La recherche de mises à jour du logiciel utilise ce dépôt de téléchargements.
Le nom du ZIP reste compatible avec Plume. Les préférences sont conservées dans
un dossier séparé des binaires.

Si une très ancienne version ne peut pas se mettre à jour automatiquement :
quitte-la depuis son icône, extrais le nouveau ZIP, puis remplace seulement
**Plume.exe** et **_internal** dans ton installation. Conserve **models** si tu
possèdes déjà le pack Eira. Pour Eira, utilise ensuite l’installateur ci-dessus.

## Un souci ou une idée ?

[Signaler un problème](https://github.com/d4vd97kat/Plume-Downloads/issues/new) :
indique la version, l’application et un exemple inventé avec le résultat attendu.
Aucun message personnel n’est nécessaire.

Pour soutenir le projet : [PayPal](https://paypal.me/davidbavol).

Ce dépôt public contient les téléchargements, les notes et les captures.
Le code de développement est conservé dans un dépôt privé.
