[**Cursed Forge Download**](https://www.curseforge.com/minecraft/mc-mods/better-campfires)

[**Modrinth Download**](https://modrinth.com/mod/better-campfires)

campfire_buffs.json
```
{
  "campfires_can_buff": true,
  "buff_radius": 6,
  "buff_check_interval": 30,
  "campfires_can_cook": true,
  "cook_radius": 4,
  "cook_check_interval": 20,
  "require_lit_campfire": true,
  "buffs": [
    {
      "effect": "minecraft:regeneration",
      "duration": 200,
      "amplifier": 0
    },
    {
      "effect": "minecraft:resistance",
      "duration": 200,
      "amplifier": 0
    }
  ],
  "cookable_items": [
    {
      "rawItem": "minecraft:cod",
      "cookTime": 200,
      "cookedItem": "minecraft:cooked_cod"
    },
    {
      "rawItem": "minecraft:salmon",
      "cookTime": 150,
      "cookedItem": "minecraft:cooked_salmon"
    },
    {
      "rawItem": "minecraft:beef",
      "cookTime": 300,
      "cookedItem": "minecraft:cooked_beef"
    },
    {
      "rawItem": "minecraft:chicken",
      "cookTime": 200,
      "cookedItem": "minecraft:cooked_chicken"
    },
    {
      "rawItem": "minecraft:mutton",
      "cookTime": 200,
      "cookedItem": "minecraft:cooked_mutton"
    },
    {
      "rawItem": "minecraft:porkchop",
      "cookTime": 250,
      "cookedItem": "minecraft:cooked_porkchop"
    },
    {
      "rawItem": "minecraft:rabbit",
      "cookTime": 200,
      "cookedItem": "minecraft:cooked_rabbit"
    },
    {
      "rawItem": "minecraft:potato",
      "cookTime": 100,
      "cookedItem": "minecraft:baked_potato"
    },
    {
      "rawItem": "minecraft:grass_block",
      "cookTime": 200,
      "cookedItem": "minecraft:dirt"
    }
  ]
}

