# Souls-Like Combat System

<a name="Gregory Allen"></a>
![date](https://img.shields.io/badge/Build%20Date-05.02.24-informational)
<a name="about"></a>
## About 
Currently engineering the logic and implementing a third-person combat system inspired by the "Souls-like" genre inspired by games such as Lies of P, simulating the game's combat dynamics. I am actively working towards creating a seamless integration of the combat system, emphasizing fluidity and responsiveness in player actions, as well as modularity in player interactions, attacks, and reactions. I utilize C++ and Unreal Engine to code and optimize the combat mechanics, focusing on precise hitboxes, enemy AI behaviors, and player attack feedback. Additionally, I created comments detailing the intricacies of the Souls-like combat system, facilitating ease of understanding.


<a name="list-of-features"></a>
## List of Mechanics Implemented
[active]:https://img.shields.io/badge/-Active-success
[depreciated]:https://img.shields.io/badge/-Depreciated-inactive
[updating]:https://img.shields.io/badge/-Updating-purple
[passing]:https://img.shields.io/badge/-Passing-success
[outdated]:https://img.shields.io/badge/-Outdated-blue
[dev]:https://img.shields.io/badge/-Unreleased-important

[version-1.0.0]:https://img.shields.io/badge/Ver.-1.0.0-ff69b4
[version-1.0.1]:https://img.shields.io/badge/Ver.-1.0.1-ff69b4
[version-1.0.2]:https://img.shields.io/badge/Ver.-1.0.2-ff69b4
[version-1.0.3]:https://img.shields.io/badge/Ver.-1.0.3-ff69b4
[version-1.0.4]:https://img.shields.io/badge/Ver.-1.0.4-ff69b4
[version-1.0.5]:https://img.shields.io/badge/Ver.-1.0.5-ff69b4
[version-dev]:https://img.shields.io/badge/Ver.-dev-important

|**Name**|**Description**|**Version**|**Testing**|**Status**|
|:------:|:-------------:|:---------:|:-------:|:--------:|
|**Basic Equipment: Weapons and Armor**| Weapon and Armor Sockets attached to Player Character, with the ability to spawn the weapons at those locations.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Pick up Actor for Equipment**|Actor within the level that spawns the equipment associated with that actor in the appropriate socket location.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Equipping/Unequipping Weapons**| Animations for equipping and unequipping weapons while not inhibiting root motion.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Combat Actor Component**| Actor Component to oversee the entire combat system. Encapulates entering and exiting combat and the various other combatfunctionalities.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Attack Combinations**| Blending of attack combinations and various delays based on the start and end of the attack sequence. Depending on user input whether to continue or reset the attack combo|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Hit Detection System**|On receiving damage from player and enemies, both health and animation systems will act accordingly.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Hit Reaction System**|Once hit, player animation at that location will play.|![active][version-1.0.0]|![dev][dev]|![dev][dev]|
|**Movement Mechanics**|Stamina system, Directional Dodge, and jumpink mechanis implementation.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Character State Manager**|Monitors character state for combat, life, and death and saves the appropriate data.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Targeting/Lock-On System**|Combat system to target and lock on to enemy characters.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Entering/Exiting Combat**| Combat system to change state from entering exiting combat, calling reset combat system appropriately and playing attack animations.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Reset Combat System**|Resets attack combinations and player state.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Character Action and Action Precedence**|Player Interactions, light attacks, heavy attacks, special stacks, and jumping attacks.|![active][version-1.0.0]|![passing][passing]|![Active][active]|
|**Enemy AI**|Enemy Character implementation.|![active][version-1.0.0]|![dev][dev]|![dev][dev]|
|**Boss AI**|Continuation of Enemy AI to include additional challenging enemy behavior.|![active][version-1.0.0]|![dev][dev]|![dev][dev]|
|**Blocking System**|Interacts with Stamina and Health system for blocking and defense.|![active][version-1.0.0]|![dev][dev]|![dev][dev]|
|**Parry System**|Continuation of blocking system to include parrying for chance combat mechanics.|![active][version-1.0.0]|![dev][dev]|![dev][dev]|
 
