# Magic-Halloween
A Halloween config setup for the [Magic Minecraft Plugin](https://www.spigotmc.org/resources/magic.1056/). This is a hard depencence and it will not work without.

**Instalation**

`/mconfig example fetch halloween https://github.com/TheDarthFather/Magic-Halloween/archive/refs/heads/main.zip`

`/mconfig example add halloween`

**Dependences:**

**1. Magic-Halloween resource pack** is needed for some custom models.
You have a few options available:
1. Use directly the [merged pack](https://download.mc-packs.net/pack/ad733ccf10d2f0a9bdb4d88e6cfe51a1322298e1.zip) between Magic-HiRess and MagicHalloween, by setting up the link into you config as per below instructions.  
2. Download the [merged pack](https://download.mc-packs.net/pack/ad733ccf10d2f0a9bdb4d88e6cfe51a1322298e1.zip) between Magic-HiRess and MagicHalloween.
3. Download the [MagicHalloweenRP](https://github.com/TheDarthFather/Magic-Halloween/blob/main/dependences/resource-pack/MagicHalloweenRP.zip) pack and merge it with the Magic Pack version of your choice.

Of course you need to merge it as well with your server resource pack, if you have one and than setup the RP as per below config. Great tool for merging RPs [here](https://merge.elmakers.com/)

_RP Config_

In all the cases you will have to edit /Magic/config/\_customizations.yml and add a line as **resource_pack: "*LinkHere*"**

Example for Option 1: `resource_pack: "https://download.mc-packs.net/pack/ad733ccf10d2f0a9bdb4d88e6cfe51a1322298e1.zip"`

**2. ModelEngine** is used for a few custom mobs.

Download the ModelEngine plugin and copy the mobs from [here](https://github.com/TheDarthFather/Magic-Halloween/tree/main/dependences/modelengine/blueprints) to the plugin blueprints folder

**3. LibDisquises** for mob disquises. 


_**Uninstall**_

`/mconfig example halloween remove`

You may want to keep the RP after uninstall if your players got custom Halloween item/wands.
