# DRAGON BALL GEKISHIN SQUADRA assets

Native model, skeleton, animation, texture, and supporting files retrieved from the installed PC game on 21 October 2026.

## Download the assets

The complete extraction is provided in ZIP parts under [Releases](https://github.com/Hum2a/dbgk-assets/releases). Download all ZIP parts from a release and extract each into the same directory. Every ZIP is independently readable; they are not split volumes. Together they recreate the extraction folder.

Git contains the file manifests, package metadata, verification results, and release archive checksums. A Git clone or GitHub's automatically generated **Source code** archives do not include the game asset binaries.

## Contents

- 19,348 `.mesh` geometry files
- 13,548 `.jmo2` native animation files
- 7,858 `.skel` skeleton files
- 22,436 `.jtex` texture files
- 6,941 `.jpfb` related prefab files
- 4 `.jtoc` asset indexes and 4 `.jarc` related archives

Total: 70,139 native asset files, 31,496,360,493 bytes before ZIP compression. Counts include package variants and non-character assets.

The `resource`, `resource_patch`, and `download` packages remain separate. Filenames retain their package ordinal and numeric asset ID. These are game-native files, not FBX, glTF, or Blender exports. Character identification, rig association, and animation conversion are not included.

## Verification

Every exported asset passed size, format-signature, and SHA-256 checks against its extraction record. The package manifests also list scanned files that were not exported; only records with `extracted: true` are included in the asset downloads. Unselected audio, scripts, effects, and unknown formats were not exported.

ZIP-part checksums are provided in `release-files.json`. Each download preserves the original relative paths.

## Attribution and rights

Extraction used an adapted version of [WistfulHopes/JPKGReader](https://github.com/WistfulHopes/JPKGReader), revision `ff08dd1eb2324c88947ddb4781218ba2add5adc2` (MIT-licensed tool).

The game assets retain their original copyrights. This repository does not grant an open-source license or other rights to the game assets.
