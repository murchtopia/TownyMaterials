<img width="1000" height="150" alt="Текст абзаца" src="https://github.com/user-attachments/assets/86a615f8-6678-4c3d-a8bb-550ab068aafe" />


# TownyMaterials:
A [Skript](https://github.com/SkriptLang/Skript) for [Towny](https://github.com/TownyAdvanced/Towny) that adds configurable resource requirements for town creation.

## Features:
- Configurable resource requirements for town creation
- Custom messages support
- YAML-based configuration

## Requirements:
- [Towny](https://github.com/TownyAdvanced/Towny)
- [Skript](https://github.com/SkriptLang/Skript)
- [skript-reflect](https://github.com/SkriptLang/skript-reflect)
- [skript-reflect](https://github.com/SkriptLang/skript-reflect)

## Configuration:
- All settings are stored in `plugins/TownyMaterials/config.yml`.  
- After making changes, reload the script using: `/sk reload TownyMaterials`

## Config Example:
```yaml
msg: "&8| You must have the following resources to create a town:"

materials:
- "256 cobblestone"
- "128 oak_log"
- "32 coal"
- "16 iron_ingot"
```
## Feedback:
Found a bug or have a suggestion? Please open an issue!
