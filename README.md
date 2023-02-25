# RollDice
An optimised and standalone RollDice system for FiveM.

Hey there,

this is a resource made by SpecialStos.

You are not allowed to sell this script by any means, this is a free script just for the general FiveM population.

If you do need any support feel free to hop on discord or make an issue through github.

Discord Server: https://discord.io/voxit
My Personal Discord: SpecialStos#0001

Don't forget to check out our Tebex store for resource you are able to purchase: https://voxit.tebex.io/

# Installation

1. Drag and drop the resource into your resource folder
2. Drag and drop the dice.png into your qb-inventory
3. Add the item into your qb-core/shared/items.lua
```lua
	['dice']                 		 = {['name'] = 'dice', 							['label'] = 'Dice', 					['weight'] = 100, 		['type'] = 'item', 		['image'] = 'dice.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = "It's a dice"},
```
4. Add start RollDice to your server.cfg
