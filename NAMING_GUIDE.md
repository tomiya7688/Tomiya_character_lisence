# Character and model naming guide

This is a naming recommendation for community clarity. It does not determine
or override the license of any character artwork.

## Player identity and model identity are different

A character/player profile can have a name and image independently from the
technical model artifact.

For example:

```text
Player profile
  name: Wise Misk / 賢者ミスク
  image: Wise Misk artwork

Model artifact
  name: My-Misk-Tune-2B
  base: Qwen...
  derived_from: official/default model
  publisher: community author
```

The reverse is also fine: an official/default model may be used while the user
changes only the player name and image.

## Community fine-tunes

For a fine-tuned or otherwise modified model, a distinct model name is
recommended.

Good examples:

- `My-Misk-Tune-2B`
- `GameFox-2B`
- `Alice-RPG-Adapter`
- `GameFox-2B — fine-tuned from Wise Misk`

Descriptive origin statements such as:

- "fine-tuned from Wise Misk"
- "Wise Misk-derived"
- "based on the default Wise Misk model"

are welcome.

## Artwork

Artwork usage follows the license declared for that specific character/asset
set. A community model does not need to keep the character's original name
just because it uses artwork whose license permits that use.

Wise Misk's final artwork license is currently undecided; do not infer MIT from
this naming guide.

## Official/community metadata

Applications and model catalogs should identify official/community status,
publisher, base model, derivation/provenance, and artifact hash separately from
the player-visible name and image.
