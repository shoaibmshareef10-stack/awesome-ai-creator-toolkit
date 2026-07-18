# ComfyUI Models Guide

## Introduction

Models are the foundation of every ComfyUI workflow. Choosing the right model greatly affects image quality, style, and consistency.

---

# Checkpoint Models

Checkpoint models are the primary AI models used to generate images.

Examples:

- SD 1.5
- SDXL
- Flux
- Pony
- Juggernaut

---

# VAE Models

VAE (Variational Autoencoder) improves image colors, sharpness, and decoding quality.

Always use a compatible VAE with your checkpoint.

---

# LoRA Models

LoRA models modify or enhance the base model.

Common uses:

- Character styles
- Clothing
- Facial expressions
- Art styles
- Backgrounds

---

# ControlNet Models

ControlNet provides greater control over image generation.

Common types:

- Canny
- Depth
- OpenPose
- LineArt
- SoftEdge

---

# Upscaler Models

Upscaler models increase image resolution while preserving quality.

Popular options:

- ESRGAN
- RealESRGAN
- 4x UltraSharp

---

# Model Organization

- Keep models in separate folders.
- Use clear file names.
- Remove unused models.
- Update models regularly.

---

# Best Practices

- Match the VAE with the checkpoint.
- Use trusted models.
- Test models before production.
- Keep backups of important models.

---

# Common Mistakes

- Wrong model selection.
- Incompatible VAE.
- Too many unused models.
- Mixing incompatible model versions.

---

# Next Step

Continue with **Extensions.md** to learn how to expand ComfyUI with additional features.
