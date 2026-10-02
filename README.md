# SSAC Listening Samples

This repository contains audio examples accompanying **SSAC: Multi-Constraint Synthetic Supervision for Direct Accent Conversion**.

The main implementation is available in the **[SSAC repository](https://github.com/eurecom-asp/SSAC)**.

The listening demo presents source speech and accent-converted samples across six target accents—Arabic, Chinese, Hindi, Korean, Spanish, and Vietnamese—together with representative comparison systems.

## Listening Demo

The interactive listening page is available at:

**https://eurecom-asp.github.io/SSAC_listening_samples/**

## Repository Structure

- `audio/`: source and converted audio samples
- `assets/`: stylesheets and supporting resources
- `js/`: JavaScript for the listening interface
- `index.html`: main listening-demo page

## SSAC

SSAC is a direct accent conversion framework that constructs synthetic supervision from multiple stochastic accent-conditioned candidates using complementary accent, content, speaker, and duration constraints.

The multi-candidate stage is used only during supervision construction. At inference time, the final converter performs single-pass generation conditioned on the source transcript and target-accent label.

For implementation details, training instructions, and reproducibility information, see:

**[eurecom-asp/SSAC](https://github.com/eurecom-asp/SSAC)**
