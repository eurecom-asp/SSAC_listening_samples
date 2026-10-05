<div align="center">

# SSAC Listening Samples

### Audio Examples for SSAC: Multi-Constraint Synthetic Supervision for Direct Accent Conversion

<p>
  <a href="https://eurecom-asp.github.io/SSAC_listening_samples/">
    <img src="https://img.shields.io/badge/🎧_LISTEN_TO_AUDIO_DEMO-8A2BE2?style=for-the-badge" alt="Listen to Audio Demo">
  </a>
</p>

### 🎧 [**Open the Interactive Listening Demo**](https://eurecom-asp.github.io/SSAC_listening_samples/)

[**Main SSAC Repository**](https://github.com/eurecom-asp/SSAC)

</div>

---

## About

This repository contains audio examples accompanying **SSAC: Multi-Constraint Synthetic Supervision for Direct Accent Conversion**.

The listening demo presents source speech and accent-converted samples across six target accents—**Arabic, Chinese, Hindi, Korean, Spanish, and Vietnamese**—together with representative comparison systems.

> **For audio examples, please visit the [interactive listening demo](https://eurecom-asp.github.io/SSAC_listening_samples/).**

---

## SSAC

SSAC is a direct accent conversion framework that constructs synthetic supervision from multiple stochastic accent-conditioned candidates using complementary accent, content, speaker, and duration constraints.

The multi-candidate stage is used only during supervision construction. At inference time, the final converter performs single-pass generation conditioned on the source transcript and target-accent label.

For implementation details, training instructions, and reproducibility information, see the main repository:

**[eurecom-asp/SSAC](https://github.com/eurecom-asp/SSAC)**

---

## Repository Structure

- `audio/`: source and converted audio samples
- `assets/`: stylesheets and supporting resources
- `js/`: JavaScript for the listening interface
- `index.html`: main listening-demo page
