# Armor Upgrades

New armors for vanilla minecraft! The new armors are `Fire`, `Ender`, `Prismarine`, `Dune` and `Sculk` armors, these new armors do not seek to create a tier more powerful than the netherite, they seek to add armors that modify other attributes so you can choose the armor that best suits your play style, that is, they are alternatives to the netherite armor.

Armor, armor toughness and durability is the same as the diamond armor set.

When a player obtains a diamond, they unlock all armor recipes

Version: `1.21.4`

## Armors

<details>
    <summary>Fire Armor</summary>
    Every armor piece have
    <ul>
        <li><code>0.1 attack_speed</code></li>
        <li><code>1 burning_time</code></li>
    </ul>
    <p></p>
    By having full armor you gain fire resistance effect and if any amor piece falls into the lava it will not burn, it will be glowing and will up to the surface.
</details>

<details>
    <summary>Ender Armor</summary>
    Every armor piece have:
    <ul>
        <li><code>+0.01 movement_speed</code></li>
    </ul>
    <p></p>
    If any armor piece falls into the void at the end, it will levitate in the air, will be glowing and will not be dispawned.
</details>

<details>
    <summary>Prismarine Armor</summary>
    Every armor piece have:
    <ul>
        <li><code>+2 max_health</code></li>
        <li><code>+0.25 water_movement_efficiency</code></li>
        <li><code>+10 oxygen_bonus</code></li>
        <li><code>+1 submerged_mining_speed</code></li>
    </ul>
    <p></p>
    By having full armor you gain conduit power effect.
</details>

<details>
    <summary>Dune Armor</summary>
    Every armor piece have:
    <ul>
        <li><code>+0.25 entity_interaction_range</code></li>
        <li><code>+0.5 entity_interaction_range</code></li>
    </ul>
</details>

<details>
    <summary>Sculk Armor</summary>
    Every armor piece have:
    <ul>
        <li><code>+1 attack_damage</code></li>
        <li><code>+0.5 sneaking_speed</code></li>
    </ul>
    <p></p>
    By having full armor you are immune to all bad effects.
</details>

## Commands

Give:

```mcfunction
/loot give @s loot armor_upgrades:<armor_name>/<armor_piece>
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