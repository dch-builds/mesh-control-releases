# Mesh Control — distribution

*[English](#english) · [Français](#français)*

## English

Binaries and updates for **Mesh Control**, a Windows application to drive a
[MeshCentral](https://meshcentral.com) server: remote desktop, terminal, file
transfer and power actions. The user interface is in French for now.

This repository holds no source code. It is only a distribution point: the
application looks for its updates here and applies them on its own.

### Installation

Download `MeshControl-win-Setup.exe` from the
[latest release](../../releases/latest) and run it. Installing requires no
administrator rights — it goes into the user's profile.

> Windows shows a SmartScreen warning on first launch, as the executable is not
> digitally signed. Click "More info", then "Run anyway".

### Updates

Once installed, the application checks for new versions on its own and only
downloads what changed — a few hundred kilobytes instead of the whole
installer.

### License and notices

Mesh Control is released under the MIT License. The third-party components it
ships with (.NET runtime, Velopack) are listed in `THIRD-PARTY-NOTICES.md`,
installed next to the application.

Mesh Control is an independent client for MeshCentral. It is not affiliated
with or endorsed by the MeshCentral project. MeshCentral is © Intel
Corporation, created by Ylian Saint-Hilaire, and licensed under the Apache
License 2.0. This application contains no MeshCentral code: it talks to
servers through their published interfaces.

Windows is a trademark of the Microsoft group of companies. Other trademarks
belong to their respective owners.

## Français

Binaires et mises à jour de **Mesh Control**, application Windows pour piloter un
serveur [MeshCentral](https://meshcentral.com) : bureau à distance, terminal,
transfert de fichiers et actions d'alimentation.

Ce dépôt ne contient aucun code source. Il sert uniquement de point de
distribution : l'application y cherche ses mises à jour et les applique
elle-même.

### Installation

Télécharger `MeshControl-win-Setup.exe` depuis la
[dernière version](../../releases/latest) et l'exécuter. L'installation ne
demande aucun droit administrateur — elle se fait dans le profil de
l'utilisateur.

> Windows affiche un avertissement SmartScreen au premier lancement,
> l'exécutable n'étant pas signé numériquement. Cliquer sur « Informations
> complémentaires » puis « Exécuter quand même ».

### Mises à jour

Une fois installée, l'application vérifie seule les nouvelles versions et ne
télécharge que ce qui a changé — quelques centaines de kilooctets plutôt que
l'installeur entier.

### Licence et mentions

Mesh Control est distribué sous licence MIT. Les composants tiers fournis avec
l'application (runtime .NET, Velopack) sont listés dans
`THIRD-PARTY-NOTICES.md`, installé à côté de l'application.

Mesh Control est un client indépendant pour MeshCentral. Il n'est ni affilié ni
approuvé par le projet MeshCentral. MeshCentral est © Intel Corporation, créé par
Ylian Saint-Hilaire, sous licence Apache 2.0. Cette application ne contient aucun
code MeshCentral : elle communique avec les serveurs via leurs interfaces
publiées.

Windows est une marque du groupe Microsoft. Les autres marques appartiennent à
leurs propriétaires respectifs.
