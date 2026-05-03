# Curly Pig

Curly Pig is a Codex digital pet package.

It contains a compact chibi pig mascot with black bean eyes, a pink snout, magenta curl markings, tiny legs, and a curly tail.

![Curly Pig](curly-pig.png)

## Files

- `pet.json` - Codex pet metadata.
- `spritesheet.webp` - 8x9 animated pet spritesheet, 1536x1872 pixels.
- `curly-pig.png` - preview image cropped from the top-left spritesheet cell.

## Install

Copy this folder into your Codex pets directory:

```bash
mkdir -p ~/.codex/pets
cp -R curly-pig ~/.codex/pets/
```

After installation, the pet metadata should be available at:

```text
~/.codex/pets/curly-pig/pet.json
```

## Metadata

```json
{
  "id": "curly-pig",
  "displayName": "Curly Pig",
  "description": "A round peach chibi pig with black bean eyes, a pink snout, magenta curl markings, tiny legs, and a curly tail.",
  "spritesheetPath": "spritesheet.webp"
}
```
