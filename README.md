# Miekri 2.0 — anciennement Plume

**Un correcteur gratuit pour écrire en français sur Windows, avec Eira pour relire le contexte.**

**[Télécharger Miekri pour Windows](https://github.com/d4vd97kat/Plume-Downloads/releases/latest/download/Plume-windows-x64.zip)** ·
[Nouveautés de la 2.0](Notes-de-version-2.0.md) ·
[Installer le modèle Eira](#activer-le-modèle-eira)

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

1. Télécharge le [ZIP Windows](https://github.com/d4vd97kat/Plume-Downloads/releases/latest/download/Plume-windows-x64.zip).
2. Fais un clic droit sur le ZIP, puis **Extraire tout** dans un dossier personnel.
3. Garde **Plume.exe** et **_internal** ensemble, puis ouvre **Plume.exe**.
   Le nom technique historique est conservé pour assurer la continuité des installations.
4. Si la correction est en pause, active-la depuis le disque central.

Miekri est prévu pour **Windows 64 bits**. Le menu donne accès au dictionnaire,
aux raccourcis et à la rédaction. Tes mots protégés, abréviations et réglages
restent personnels. Fermer la fenêtre peut laisser le correcteur actif près
de l’horloge ; son menu permet de le quitter.

## Activer le modèle Eira

Les règles de correction locale fonctionnent sans télécharger de grand modèle.
Pour ajouter la relecture avec le modèle Eira :

1. Installe d’abord Miekri 2.0.
2. Télécharge le [pack d’installation Eira](https://github.com/d4vd97kat/Plume-Downloads/releases/latest/download/Miekri-Eira-Installer-windows-x64.zip).
3. Extrais son contenu **dans le même dossier que Plume.exe**.
4. Ouvre **Installer-Eira.bat**. Il télécharge environ **5 Go** et vérifie les
   fichiers avant de les installer. Prévois au moins **6 Go libres**.
5. Quitte Miekri depuis son icône près de l’horloge, puis relance-le.

Le modèle est Qwen3-8B, préentraîné, avec un runtime local. Ses besoins en mémoire
et ses performances dépendent du PC ; ce grand modèle n’est pas adapté à toutes
les machines. Aucun téléchargement du modèle ne démarre à l’ouverture de Miekri.
Si un pack conforme est déjà présent, l’installateur le vérifie sans le remplacer.

L’accueil distingue la disponibilité d’Eira de celle du correcteur local.
La correction locale peut rester active pendant le chargement du modèle.

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
