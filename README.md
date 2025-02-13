# Armor Upgrades

New armors for vanilla minecraft!

- `Dune`
- `Fire`
- `Prismarine`
- `Ender`
- `Sculk`

These new armors do not seek to create a tier more powerful than the netherite, they seek to add armors that modify other attributes so you can choose the armor that best suits your play style, that is, they are alternatives to the netherite armor.

When a player obtains a diamond he unlocks all the armor recipes.

Version: `1.21.4`

## Armors

### Dune

All armor parts have:
- `+0.25 entity_interaction_range`
- `+0.5 entity_interaction_range`

### Prismarine

All armor parts have:
- `+2 max_health`
- `+0.25 water_movement_efficiency`
- `+10 oxygen_bonus`
- `+1 submerged_mining_speed`

### Ender

All armor parts have:
- `+0.01 movement_speed`

If any piece of armor falls into the void at the end, it will float in the air, will glow and will not be dispawned.

### Fire

All armor parts have:
- `+0.1 attack_speed`
- `-1 burning_time`

By having full armor you gain resistance against fire and if a piece of armor falls into the lava it will not burn, it will be glowing and will rise to the surface of the lava.

### Sculk

All armor parts have:
- `+1 attack_damage`
- `+0.5 sneaking_speed`

By having full armor you are immune to all bad effects.

## Commands

Give:

```mcfunction
/loot give @s loot armor_upgrades:`<armor_name>`/`<armor_piece>`
```

Give examples:

```mcfunction
/loot give @s loot armor_upgrades:ender/chestplate

/loot give @s loot armor_upgrades:dune/boots

/loot give @s loot armor_upgrades:prismarine/all
```

Disable:

```mcfunction
/datapack disable "file/armor-upgrades.zip"
```

Enable:

```mcfunction
/datapack enable "file/armor-upgrades.zip"
```

## License

MIT