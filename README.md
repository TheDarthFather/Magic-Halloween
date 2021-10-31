# Magic-Halloween
A Halloween config setup for the [Magic Minecraft Plugin](https://www.spigotmc.org/resources/magic.1056/). This is a hard depencence and it will not work without.

**Instalation**

`/mconfig example fetch halloween https://github.com/TheDarthFather/Magic-Halloween/archive/refs/heads/main.zip`

`/mconfig example add halloween`

**Dependences:**

**1. Magic-Halloween resource pack** is needed for some custom models.
You have a few options available:
1. Use directly the [merged pack](https://download.mc-packs.net/pack/ad733ccf10d2f0a9bdb4d88e6cfe51a1322298e1.zip) between Magic-HiRess and MagicHalloween, by setting up the link into you config as per below instructions.  
2. Download the [merged pack](https://download.mc-packs.net/pack/ad733ccf10d2f0a9bdb4d88e6cfe51a1322298e1.zip) between Magic-HiRess, MagicHalloween and merge it with your server resource pack, if you have one. 
3. Download the [MagicHalloweenRP](https://github.com/TheDarthFather/Magic-Halloween/raw/dependences/dependences/resource-pack/MagicHalloweenRP.zip) pack and merge it with the Magic Pack version of your choice and with your server resource pack, if you have one. 



_RP Configuration_

In all the cases you will have to edit /Magic/config/\_customizations.yml and add this line `resource_pack: "*RPLinkHere*"`

Current working setup for Option 1: `resource_pack: "https://download.mc-packs.net/pack/ad733ccf10d2f0a9bdb4d88e6cfe51a1322298e1.zip"`


**2. ModelEngine** is used for a few custom mobs.

Download the ModelEngine plugin and copy the mobs from [here](https://github.com/TheDarthFather/Magic-Halloween/tree/dependences/dependences/modelengine/blueprints) to the plugin blueprints folder

**3. LibDisquises** for mob disquises. 


_**Uninstall**_

`/mconfig example halloween remove`

You may want to keep the RP after uninstall if your players got custom Halloween item/wands.

**Features**

- 50% from the Overwold mobs are replaced by special Halloweens mobs
- All the mobs will have a smal change to pison, slow, hunger you.
- All the mobs have great resistances to physical damage.
- All the mobs will drop SP and a few custom weapons. 
- Each weapon comes in 2 variants .. one Magical, that rolls different stats on drop and a Unique one that have also a passive spell (ex CriticalChance). 
![2021-10-31_00 48 10](https://user-images.githubusercontent.com/23462204/139560597-0717c227-cc6b-408f-9c80-9121e463f62e.png)
![2021-10-31_00 48 04](https://user-images.githubusercontent.com/23462204/139560599-edf5e20a-c03b-4ed4-ad95-8d538a900044.png)

_Current Mobs_

Ghost: 
![2021-10-31_00 53 48](https://user-images.githubusercontent.com/23462204/139560625-0807e3ab-71e3-4d22-bdd3-640c6f9e453b.png)

Headless Horseman: 
![2021-10-31_00 49 34](https://user-images.githubusercontent.com/23462204/139560628-c3fda435-29f7-4317-9743-e5a82e174b68.png)

ScareCrow: 
![2021-10-31_00 48 49](https://user-images.githubusercontent.com/23462204/139560641-b94dc8f6-06f6-4c80-b3ea-4bda5b0f05d6.png)

Werewolf: 
![2021-10-31_00 50 14](https://user-images.githubusercontent.com/23462204/139560645-ce42475b-c5c3-4eb4-a122-c6c24b3bfe21.png)

Strange Spider: 
![2021-10-31_00 49 46](https://user-images.githubusercontent.com/23462204/139560648-ab6e19c4-9be8-4164-85bf-18b45cf3a5d5.png)

Zombie: 
![2021-10-31_00 50 24](https://user-images.githubusercontent.com/23462204/139560654-39bc8d96-d37d-411a-8fe8-72537f8e6828.png)

**To Do**

- Add Haunted House and additional mobs

**Other**

Great tool for merging RPs [here](https://merge.elmakers.com/)
