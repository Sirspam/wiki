- - -
sidebar: auto description: Learn how to create your own mods!
- - -

# Créer des mods
<<<<<<< HEAD
=======

## Injection de mods
Beat Saber _**ne supporte pas**_ nativement les mods.
>>>>>>> master

Beat Saber _**does not**_ have built in mod support.

Development for [PC](#pc-mod-development) and [Quest standalone](#quest-mod-development) are two vastly different workflows.

## PC Mod Development

### Injecting Mods
Instead, most mods within the mod installer rely on [BSIPA (Beat Saber Illusion Plugin Architecture)](https://github.com/nike4613/BeatSaber-IPA-Reloaded/) to inject plugins into the game, as well as providing some useful tools for us modders.

<<<<<<< HEAD
For those of you who prefer [BepInEx](https://github.com/BepInEx/BepInEx) over either of these options, Bepis has created a loader for BSIPA plugins, available [here](https://github.com/BepInEx/BepInEx.BSIPA.Loader). As for developing Beat Saber plugins with the BepInEx plugin API, a generic guide exists on their [documentation site](https://bepinex.github.io/bepinex_docs/v5.0/articles/dev_guide/plugin_tutorial/index.html), but other than that you're kinda on your own.

### Project Setup
If you are interested in creating a Beat Saber mod, but do not have a template or Visual Studio template set up, [follow the Intro guide to get your project all set up](./pc-mod-dev-intro.md).
=======
Pour ceux qui préfèrent [BepInEx](https://github.com/BepInEx/BepInEx) plutôt que ces options, Bepis a créé un loader pour les plugins BSIPA, disponible [ici](https://github.com/BepInEx/BepInEx.BSIPA.Loader). Cependant, pour développer des extensions Beat Saber avec l'API du plugin BepInEx, un guide générique existe sur [le site de leur documentation](https://bepinex.github.io/bepinex_docs/v5.0/articles/dev_guide/plugin_tutorial/index.html), autrement vous devrez vous débrouiller tout seul.
>>>>>>> master

#### Ready to go?
Check out the [links below](#other-links) for documentation relating to Unity and related tooling. If you have any questions, the best place to ask is in the `#pc-mod-dev` channel on the [BSMG Discord](https://discord.gg/beatsabermods)

### Launch args
Helpful launch arguments that will make modding / debugging easier.

<!-- markdownlint-disable MD013 -->
| Argument&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description                                                                                                                                                                                                           |
| -------------------------------------------------------------------------------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--verbose`                                                                                  | Enables the output log window for IPA. This will show the debug console that mods use.                                                                                                                                |
| `fpfc`                                                                                       | "First Person Flying Controller"<br /><br />This allows you to use WASD and the mouse to navigate around the menu in game. This makes testing much easier, because you don't have to put on your headset! |
| `-vrmode oculus`                                                                             | If you are running Beat Saber through Steam, this allows you to play the game on an Oculus headset.                                                                                                                   |
<!-- markdownlint-enable MD013 -->

<<<<<<< HEAD
### Other Links

=======
<!-- markdownlint-disable MD013 -->
| Argument&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description                                                                                                                                                                                                           |
| -------------------------------------------------------------------------------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--verbose`                                                                                  | Active la fenêtre de sortie des logs d'IPA. Cela affichera la console de débogage que les mods utilisent.                                                                                                             |
| `fpfc`                                                                                       | "First Person Flying Controller"<br /><br />Cela vous permet d'utiliser WASD et la souris pour naviguer dans le menu en jeu. C'est beaucoup plus facile de tester avec, pas besoin de mettre son casque ! |
| `-vrmode oculus`                                                                             | Si vous lancez Beat Saber à travers Steam, cela vous permet de jouer le jeu dans un casque Oculus.                                                                                                                    |
<!-- markdownlint-enable MD013 -->

## Autres liens

>>>>>>> master
* [BeatMods](https://beatmods.com)
* [Lignes directrices pour l'approbation sur BeatMods](https://docs.google.com/document/d/15RBVesZdS-U94AvesJ2DJqcnAtgh9E2PZOcbjrQle5Y/edit?usp=sharing)
* [API Unity Scripting](https://docs.unity3d.com/ScriptReference/index.html)
* [dnSpy](https://github.com/0xd4d/dnSpy)
* [Harmony](https://github.com/pardeike/Harmony)
* [Beat Saber IPA](https://bsmg.github.io/BeatSaber-IPA-Reloaded/)
<<<<<<< HEAD

## Quest Mod Development

The following guide covers most of the concepts you will need for creating mods for the Quest. This includes but is not limited to:

* Hooking
* Configuration using `config-utils`
* Manual configuration
* User Interfaces using `questui` or `QUC`

Visit the [Quest Mod Development Intro](./quest-mod-dev-intro.md) page for more information on getting started!
=======
>>>>>>> master
