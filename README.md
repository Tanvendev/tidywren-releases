# TidyWren : versions à télécharger

**Français** · [English below](#english)

TidyWren range et vérifie votre collection de fichiers de découpe (SVG) et de broderie
machine, sur votre PC Windows, hors ligne, sans compte. Il lit vos lots jusque dans les
ZIP sans rien extraire, trouve les doublons et les fichiers cassés, et ne supprime jamais
rien : ce que vous écartez va dans une corbeille sûre, réversible.

Ce dépôt ne contient que les versions publiées. Le code source est privé.

## Télécharger

Ouvrez la page [Releases](https://github.com/Tanvendev/tidywren-releases/releases/latest)
et téléchargez `TidyWren-Setup-x.y.z.exe`. L'installation se fait dans votre profil
Windows, sans mot de passe administrateur. Windows 10 (1809 ou plus récent) et
Windows 11, 64 bits.

## Vérifier ce que vous avez téléchargé

**L'empreinte.** Chaque version publie l'empreinte SHA-256 de l'installateur dans ses
notes. Dans PowerShell, depuis le dossier Téléchargements :

```powershell
Get-FileHash .\TidyWren-Setup-1.0.0.exe -Algorithm SHA256
```

Les deux empreintes doivent être identiques, caractère pour caractère.

**La signature.** L'installateur est signé. Clic droit sur le fichier, **Propriétés**,
onglet **Signatures numériques** : la signature doit être déclarée valide et émise par
« Certum Code Signing 2021 CA ». Un installateur sans cet onglet, ou dont la signature
est invalide, ne vient pas d'ici : ne le lancez pas.

## Vos données

TidyWren ne se connecte à rien et n'envoie rien. Ses données (index, corbeille sûre,
profil) vivent dans `%USERPROFILE%\.tidywren` ; la désinstallation ne les supprime pas.

## Prix, contact

Le prix et les conditions de chaque version sont sur
[tanven.dev/tidywren](https://tanven.dev/tidywren/). Éditeur : Tanven.
Contact : contact@tanven.dev.

---

<a id="english"></a>
# TidyWren: downloads

TidyWren tidies and checks your cut-file (SVG) and machine embroidery collection, on your
Windows PC, offline, with no account. It reads your bundles right inside their ZIPs
without extracting anything, finds duplicates and broken files, and never deletes a
thing: whatever you set aside goes to a safe bin you can undo.

This repository only holds published releases. The source code is private.

## Download

Open the [Releases](https://github.com/Tanvendev/tidywren-releases/releases/latest) page
and download `TidyWren-Setup-x.y.z.exe`. It installs into your own Windows profile, with
no administrator password. Windows 10 (1809 or later) and Windows 11, 64-bit.

## Check what you downloaded

**The hash.** Each release publishes the SHA-256 hash of the installer in its notes. In
PowerShell, from your Downloads folder:

```powershell
Get-FileHash .\TidyWren-Setup-1.0.0.exe -Algorithm SHA256
```

Both hashes must match, character for character.

**The signature.** The installer is signed. Right-click the file, **Properties**,
**Digital Signatures** tab: the signature must be reported as valid and issued by
“Certum Code Signing 2021 CA”. An installer without that tab, or with an invalid
signature, does not come from here: do not run it.

## Your data

TidyWren connects to nothing and sends nothing. Its data (index, safe bin, profile)
lives in `%USERPROFILE%\.tidywren`; uninstalling does not remove it.

## Price, contact

Price and terms for each release are on
[tanven.dev/en/tidywren](https://tanven.dev/en/tidywren/). Publisher: Tanven.
Contact: contact@tanven.dev.
