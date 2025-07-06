# RoguelikeSystem

Basic roguelike weapon and upgrades systen
Made in Unreal Engine 5 using blueprints

<p align="center">
  <img src="Assets/Gifs/gameplay.gif"><br/>
</p>

## Description
Weapon and upgrade functionalities are split into seperate components. This architecture allows for easy creation of new weapons/upgrades with unique functionalities.
By simply changing the components of a weapon you can easily change its parameters and how it functions. 
The weapon and upgrade classes do not know how they function, they only call their corresponding components to handle the functionality.

## Features
- **Weapons**
  1. Rifle
  2. Pistol
- **Upgrades**
  1. Damage up
  2. Attack speed up
  3. Laser
 
