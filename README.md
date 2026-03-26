# Pmnox AutoHDR Shader

This repository contains the AutoHDR shader:

- `Shaders/Pmnox/Pmnox_PerceptualBoost.fx`

## Profiles

The shader includes 4 profiles:

1. `Profile 1 (SpecialK v1)`
2. `Profile 2 (High Boost)`
3. `Profile 3 (SpecialK v2 preset equivalent)`
4. `Profile 4`

## Notes (SpecialK Perceptual Boost)

This AutoHDR shader uses SpecialK's Perceptual Boost concept: it adjusts the image’s luminance in a non-linear way to improve perceived brightness and contrast for HDR-like output.

Start with `Profile 1 (SpecialK v1)` for the closest match to the original SpecialK behavior, then try `Profile 3 (SpecialK v2 preset equivalent)` for the updated preset. If you want a stronger “punch”, try `Profile 2 (High Boost)`.

