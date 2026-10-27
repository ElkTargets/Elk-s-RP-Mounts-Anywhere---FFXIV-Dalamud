# 🦌 Elk's RP Mounts Anywhere

**Bring your mounts into the story.** ✨

Ever wanted to park your car in a city, bring a chair mount into a house, or simply hang out with your favorite mount during an RP scene? That's exactly why I made **Elk's RP Mounts Anywhere**.

This Dalamud plugin lets you use mounts as **cosmetic appearances** in places where you normally couldn't summon them. And yes: **modded mounts are compatible too!** 💚💜

The goal is simple: more freedom for RP, without extra speed or flight.

[🇫🇷 Français](#-français) · [🇬🇧 English](#-english)

---

## 🇫🇷 Français

### C'est quoi, exactement ?

Vous connaissez ce moment où votre personnage devrait pouvoir s'installer sur sa monture pour une scène RP… mais où le jeu vous dit non parce que vous êtes en ville ou dans une maison ?

**Elk's RP Mounts Anywhere** est né pour ça. Le plugin permet d'afficher vos montures comme un élément cosmétique, où vous en avez besoin pour vos scènes RP, tout en continuant à vous déplacer normalement.

Et le meilleur : **les montures moddées sont compatibles !** Si vos mods et votre système de synchronisation sont correctement configurés, vos amis peuvent aussi voir leur apparence personnalisée.

### Ce que vous pouvez faire

- Faire apparaître vos montures en ville, en intérieur et dans vos lieux de RP.
- Les utiliser directement depuis vos **barres de raccourcis**, avec vos touches habituelles.
- Choisir une monture dans le menu du plugin, retrouver vos favoris et créer des macros.
- Descendre de votre monture facilement.
- Synchroniser l'apparence de vos montures avec vos amis via **Moodles** et un outil de synchronisation compatible.
- Profiter des **montures moddées**, y compris lorsque leurs apparences sont partagées avec vos amis.
- Utiliser le plugin en **français ou en anglais**.

Il s'agit uniquement d'un affichage cosmétique : **pas de bonus de vitesse, pas de vol ajouté**.

### Installation

**Prérequis :** FINAL FANTASY XIV et XIVLauncher / Dalamud. Pour la synchronisation entre joueurs, il faut aussi **Moodles** et un système de synchronisation compatible avec ses statuts (ainsi que les mods concernés, si vous utilisez des apparences moddées).

1. En jeu, ouvrez `/xlsettings` → **Experimental** → **Custom Plugin Repositories**.
2. Ajoutez l'adresse du dépôt :

   ```text
   https://raw.githubusercontent.com/ElkTargets/Elk-s-RP-Mounts-Anywhere---FFXIV-Dalamud/main/pluginmaster.json
   ```

3. Activez ce dépôt, puis enregistrez.
4. Ouvrez `/xlplugins`, cherchez **Elk's RP Mounts Anywhere** et installez-le.
5. Lancez `/emount` et suivez le message de bienvenue.

> **À noter :** le lien du dépôt Dalamud fonctionnera une fois `pluginmaster.json` publié sur la branche `main`. En attendant, retrouvez les fichiers de la version actuelle dans les [Releases GitHub](https://github.com/ElkTargets/Elk-s-RP-Mounts-Anywhere---FFXIV-Dalamud/releases/tag/v1.0.2.3).

**Pour installer Moodles**, ajoutez également le dépôt [SeaOfStars](https://github.com/Ottermandias/SeaOfStars) à vos Custom Plugin Repositories :

```text
https://raw.githubusercontent.com/Ottermandias/SeaOfStars/main/repo.json
```

Moodles transporte les informations de monture dans ses statuts. **Pour que vos amis les reçoivent**, vous devez aussi avoir un service de synchronisation compatible configuré entre vous : Moodles seul ne relie pas deux clients à distance.

### Commandes pratiques

| Commande | À quoi elle sert |
| --- | --- |
| `/emount` | Ouvrir le menu du plugin |
| `/emount welcome` | Revoir le message de bienvenue |
| `/emount setup` | Ouvrir l'assistant Moodles |
| `/emount toggle 340` | Activer / retirer la monture 340 (exemple) |
| `/emount off` | Descendre de la monture cosmétique |

### Un retour, une idée, un bug ?

N'hésitez pas à m'envoyer un message privé sur Discord : **@elktargets**. Je serai ravi de voir ce que vous faites du plugin en RP !

☕ [Ko-fi — xxgothcatxx](https://ko-fi.com/xxgothcatxx) *(oui, la page est encore en préparation 😅)*

---

## 🇬🇧 English

### What's this plugin about?

Ever wanted to pull up in your car mount in a city, bring a chair mount indoors, or just keep your favorite mount around for an RP scene, only for the game to say no?

That's what **Elk's RP Mounts Anywhere** is for. It lets you use mounts as **cosmetic appearances** in places where you normally can't summon them, while still being able to move around.

And yes, **modded mounts work too!** With your mods and a compatible sync setup in place, your friends can see their customized appearances as well.

### What can you do with it?

- Show off your mounts in cities, interiors, and other RP spots.
- Summon them straight from your **hotbars / shortcut bars**, using your usual keybinds.
- Pick mounts from the plugin menu, save favorites, and make macros.
- Dismount easily when you're done.
- Share mount appearances with friends through **Moodles** and a compatible sync tool.
- Use **modded mounts**, including shared modded appearances.
- Switch between **English and French**.

Everything is cosmetic: **no extra movement speed and no added flight**.

### Installation

**You'll need:** FINAL FANTASY XIV and XIVLauncher / Dalamud. For multiplayer sync, you'll also need **Moodles**, a compatible status-sync service, and the relevant mods if you're using custom mount appearances.

1. In-game, open `/xlsettings` → **Experimental** → **Custom Plugin Repositories**.
2. Add this repository URL:

   ```text
   https://raw.githubusercontent.com/ElkTargets/Elk-s-RP-Mounts-Anywhere---FFXIV-Dalamud/main/pluginmaster.json
   ```

3. Enable the repository and save.
4. Open `/xlplugins`, find **Elk's RP Mounts Anywhere**, and install it.
5. Type `/emount` and follow the welcome screen.

> **Note:** This Dalamud repository URL will work once `pluginmaster.json` is published on `main`. Until then, you can find the current build on [GitHub Releases](https://github.com/ElkTargets/Elk-s-RP-Mounts-Anywhere---FFXIV-Dalamud/releases/tag/v1.0.2.3).

**To install Moodles**, add the [SeaOfStars](https://github.com/Ottermandias/SeaOfStars) repository as well:

```text
https://raw.githubusercontent.com/Ottermandias/SeaOfStars/main/repo.json
```

Moodles carries the mount state, but **a compatible sync service is still needed to send that state to other players**. Moodles alone doesn't connect two game clients over the internet.

### Useful commands

| Command | What it does |
| --- | --- |
| `/emount` | Open the plugin menu |
| `/emount welcome` | Replay the welcome message |
| `/emount setup` | Open the Moodles setup wizard |
| `/emount toggle 340` | Toggle mount 340 (example) |
| `/emount off` | Dismount your cosmetic mount |

### Questions, ideas, or found a bug?

Feel free to DM me on Discord: **@elktargets**. I'd love to see how you use the plugin in your RP scenes!

☕ [Ko-fi — xxgothcatxx](https://ko-fi.com/xxgothcatxx) *(yes, the page is still a work in progress 😅)*

---

*Made for RP. Not affiliated with Square Enix, XIVLauncher, or the Dalamud team.*
