# TownyMaterials
Skript for Towny that adds resource requirements for creating towns.

<img width="592" height="90" alt="preview" src="https://github.com/user-attachments/assets/b544d71e-51ab-43f8-aaea-80a6bbd24e83" />

## Requirements
- Towny - https://github.com/TownyAdvanced/Towny
- Skript - https://github.com/SkriptLang/Skript
- Skript-YAML - https://github.com/Sashie/skript-yaml
- Skript-Reflect - https://github.com/SkriptLang/skript-reflect

## Installation
1. Download `TownyMaterials.sk`
2. Put it into `plugins/Skript/scripts/`
3. Reload Skript
4. Edit `config.yml` in `plugins/TownyMaterials/`
5. Reload script:
`/sk reload TownyMaterials`

## Config example

```yaml
msg: "&8| You must have the following resources to create a town:"

materials:
- 256 cobblestone
- 128 oak_log
- 32 coal
- 16 iron_ingot
