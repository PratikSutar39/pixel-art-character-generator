# High-Resolution Pixel Art Character Generator (ComfyUI + FLUX)

## Overview
This project presents a modular ComfyUI workflow that generates **high-resolution pixel art game characters from user images**, combining **identity-preserving LoRA fine-tuning** with **FLUX-based texture synthesis**.

The workflow is designed to solve common pixel art generation issues such as identity loss, low-resolution outputs, and texture inconsistency.

---

## Key Features
- Identity-preserving character generation using a dedicated **face LoRA**
- Style control via a separate **pixel art LoRA**
- High-resolution outputs using **FLUX texture synthesis**
- Fully modular and reusable **ComfyUI workflow**
- Game-ready pixel art suitable for modern indie and mobile games

---

## Architecture Overview
**Dual-LoRA Strategy**
- **Identity LoRA:** Trained on user facial images
- **Style LoRA:** Trained exclusively on pixel art datasets

This separation prevents overfitting and allows precise control over identity and visual style.

---

## Example Output
![Pixel Art Output](examples/outputs/sample.png)

---

## Tech Stack
- ComfyUI
- FLUX
- LoRA fine-tuning
- Diffusion-based image generation

---

## Repository Structure

pixel-art-character-generator/
├── workflows/
│ └── comfyui_workflow.json
├── loras/
│ ├── identity_lora/
│ └── style_lora/
├── examples/
│ └── outputs/
├── README.md

---

## Skills Demonstrated
- Generative AI workflow engineering
- LoRA training and inference
- Identity vs style disentanglement
- High-resolution pixel art synthesis
- Applied diffusion model design

---

## Notes
LoRA weights are not included in this repository due to size and privacy considerations.
