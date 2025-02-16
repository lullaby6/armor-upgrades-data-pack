# Armor Upgrades

[![Latest Version](https://img.shields.io/github/v/release/lullaby6/armor-upgrades-data-pack?color=blueviolet&logo=github "View latest release")](https://github.com/lullaby6/armor-upgrades-data-pack/releases) 
[![Discord Badge](https://img.shields.io/discord/1327308441324097681?label=discord&color=blue&logo=discord "Join our Discord Server")](https://discord.gg/5UdcDa5xNC) 
[![Modrinth Badge](https://img.shields.io/modrinth/dt/armor-upgrades?label=modrinth&logo=modrinth "View our Modrinth page")](https://modrinth.com/datapack/armor-upgrades) 
[![License Badge](https://img.shields.io/badge/license-mit-green "View the License")](https://github.com/lullaby6/armor-upgrades-data-pack/blob/main/LICENSE) 
[![Issues Badge](https://img.shields.io/github/issues/lullaby6/armor-upgrades-data-pack?color=orange&logo=github "View or open an issue")](https://github.com/lullaby6/armor-upgrades-data-pack/issues)

![bg](https://raw.githubusercontent.com/lullaby6/armor-upgrades-data-pack/refs/heads/main/images/bg.png)

## 📖 Description

New armors for vanilla minecraft! The new armors are `Fire`, `Ender`, `Prismarine`, `Dune` and `Sculk` armors, these new armors do not seek to create a tier more powerful than the netherite, they seek to add armors that modify other attributes so you can choose the armor that best suits your play style, that is, they are alternatives to the netherite armor.

When a player obtains a diamond, they unlock all armor recipes

Version: `1.21.4`

## 📂 Installation

Move the downloaded file in the path `.minecraft/saves/[world]/datapacks`

## 👾 Bugs/Issues

Please report any bug/issues to the [Discord Server](https://discord.gg/5UdcDa5xNC) in the `bugs` channel, or create a issue in the [Github Repostiroy](https://github.com/lullaby6/armor-upgrades-data-pack/issues), or a comment in [Planet Minecraft](https://www.planetminecraft.com/data-pack/armor-upgrades-more-armors-1-21-4).

## ⚔️ Armors

All armors durability is the same as the diamond armor set, and the armor and armor toughness is an intermediate between iron armor and diamond armor.

<details>
    <summary>Fire Armor</summary>
    Every armor piece have
    <ul>
        <li><code>+0.1 attack_speed</code></li>
        <li><code>+1 burning_time</code></li>
    </ul>
    <p></p>
    By having full armor you gain fire resistance effect and if any armor piece falls into the lava it will not burn, it will be glowing and will up to the surface.
    <p></p>
    <h3>🛠️ Recipe</h3>
    <p></p>
    <img src="https://raw.githubusercontent.com/lullaby6/armor-upgrades-data-pack/refs/heads/main/images/recipes/fire.png" alt="Fire Armor Recipe">
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
        <li><code>+0.5 block_interaction_range</code></li>
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

## ⌨️ Commands

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

## 🪪 License

[MIT](https://github.com/lullaby6/armor-upgrades-data-pack/blob/main/LICENSE)