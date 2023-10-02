---
description: Nintendo
---

# Game Boy Color 2 players

<div align="left">

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/gbc2players.svg" alt=""><figcaption></figcaption></figure>

</div>

Ce système permet d'émuler l'utilisation du link cable qui permet de jouer en connectant 2 Game Boys.

Ci-dessous la liste des jeux compatibles (en anglais) :

{% embed url="https://en.wikipedia.org/wiki/List_of_multiplayer_Game_Boy_games" %}

## Information

<table data-header-hidden><thead><tr><th width="184"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Émulateur</strong></td><td><ul><li>libretro : tgbdual</li><li>libretro: sameboy</li></ul></td><td></td></tr><tr><td><strong>Dossier des jeux</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> gbc2players</td><td></td></tr><tr><td><strong>Extensions</strong></td><td>.gbc .zip .m3u .7z</td><td></td></tr></tbody></table>

## BIOS

<table><thead><tr><th width="187">Fichier BIOS</th><th width="98">Dossier</th><th>md5</th></tr></thead><tbody><tr><td>gb_bios.bin</td><td><code>\bios</code></td><td>32fbbd84168d3482956eb3c5051637f5</td></tr><tr><td>gbc_bios.bin</td><td><code>\bios</code></td><td>dbfce9db9deaa2567f6a84fde55f9680</td></tr></tbody></table>

## Contrôles

| RetroBat                                                                           | Game Boy Color |
| ---------------------------------------------------------------------------------- | -------------- |
| START                                                                              | START          |
| SELECT                                                                             | SELECT         |
| D-PAD                                                                              | D-PAD          |
| Stick analogique gauche                                                            | D-PAD          |
| Stick analogique droit                                                             |                |
| ![A](<../../../../.gitbook/assets/image (19).png>)                                 | B              |
| ![B](<../../../../.gitbook/assets/image (6).png>)                                  | A              |
| <img src="../../../../.gitbook/assets/image (34).png" alt="" data-size="original"> |                |
| <img src="../../../../.gitbook/assets/image (32).png" alt="" data-size="line">     |                |
| L1                                                                                 |                |
| R1                                                                                 |                |
| L2                                                                                 |                |
| R2                                                                                 |                |
| L3                                                                                 |                |
| R3                                                                                 |                |

<div align="left">

<figure><img src="https://i.imgur.com/ptx8LTP.png" alt=""><figcaption></figcaption></figure>

</div>

## Information spécifique au système

### Comment jouer à 2 avec 2 cartouches de jeux différentes (Pokemon)

Le core libretro: sameboy permet de simuler un câble link avec 2 cartouches de jeu différentes, pour cela, il faut créer un fichier .m3u contenant le nom des 2 fichiers de jeux à utiliser (1 jeu par ligne):



<div align="left">

<figure><img src="https://i.imgur.com/obmo6y9.png" alt=""><figcaption></figcaption></figure>

</div>

Les 2 fichiers listés dans le .m3u doivent exister dans le dossier `roms\gb2players`
