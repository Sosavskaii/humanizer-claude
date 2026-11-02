# Humanizer : ton texte ne sonne plus ChatGPT

Le skill montré sur [@sosav.ai](https://www.instagram.com/sosav.ai/). Tu lui donnes un texte écrit par une IA, il le réécrit pour qu'il sonne comme une vraie personne, sans changer ce qu'il dit.

- Il repère **26 tics de l'IA** : « C'est pas juste un outil, c'est une révolution », « Et honnêtement ? », les phrases qui sonnent profond mais ne disent rien…
- En test à l'aveugle, des juges ont préféré sa réécriture **16 fois sur 16** (source : le dépôt d'origine).
- Il est fait pour tes lecteurs, **pas pour tromper les détecteurs d'IA** : son auteur précise que les détecteurs repèrent encore la plupart de ses textes.

## Ce qu'il te faut

**Claude Code** (abonnement Claude), ou Claude sur le site claude.ai.

## Installation

Le plus simple : colle le lien de ce dépôt dans Claude Code et demande-lui d'installer le skill.

Ou à la main :

```bash
git clone https://github.com/Sosavskaii/humanizer-claude.git
```

puis copie le dossier dans `~/.claude/skills/humanizer` (sur Windows : `C:\Users\<toi>\.claude\skills\humanizer`).

Sur claude.ai : télécharge ce dépôt en ZIP (**Code → Download ZIP**), puis importe-le comme skill dans les réglages.

## Utilisation

Dans Claude, tape `/humanizer` puis colle ton texte.

## Crédits

Humanizer est créé par Siqi Chen ([blader/humanizer](https://github.com/blader/humanizer)), sous licence MIT (voir `LICENSE`). Le README d'origine, en anglais, est dans `README.en.md`.
