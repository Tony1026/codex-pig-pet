# Codex Pig Pet

Codex Pig Pet is a Codex digital pet package.

It contains a compact chibi pig mascot with black bean eyes, a pink snout, magenta curl markings, tiny legs, and a curly tail.

![Codex Pig Pet](codex-pig-pet.png)

## Files

- `pet.json` - Codex pet metadata.
- `spritesheet.webp` - 8x9 animated pet spritesheet, 1536x1872 pixels.
- `codex-pig-pet.png` - preview image cropped from the top-left spritesheet cell.

## Install

Copy this folder into your Codex pets directory:

```bash
mkdir -p ~/.codex/pets
cp -R codex-pig-pet ~/.codex/pets/
```

After installation, the pet metadata should be available at:

```text
~/.codex/pets/codex-pig-pet/pet.json
```

## Metadata

```json
{
  "id": "codex-pig-pet",
  "displayName": "Codex Pig Pet",
  "description": "A round peach chibi pig pet with black bean eyes, a pink snout, magenta curl markings, tiny legs, and a curly tail.",
  "spritesheetPath": "spritesheet.webp"
}
```
