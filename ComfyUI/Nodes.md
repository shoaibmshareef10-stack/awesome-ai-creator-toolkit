# ComfyUI Nodes Guide

## Introduction

Nodes are the building blocks of every ComfyUI workflow. Each node performs a specific task, and together they create a complete image generation pipeline.

---

# Checkpoint Loader

Loads the AI model used for image generation.

---

# CLIP Text Encode

Converts your text prompt into information the AI model can understand.

---

# Negative Prompt

Defines what you do **not** want in the generated image.

Example:

blurry, low quality, watermark, extra fingers, deformed face

---

# Empty Latent Image

Creates the initial latent space where the image will be generated.

---

# KSampler

The core generation node.

Controls:

- Sampling Steps
- CFG Scale
- Sampler
- Seed

---

# VAE Decode

Converts the latent image into a visible image.

---

# Save Image

Saves the final generated image.

---

# Upscale Node

Improves image resolution while preserving quality.

---

# ControlNet

Provides better control over pose, depth, edges, and composition.

---

# LoRA Loader

Loads lightweight models that change character styles, clothing, faces, or artistic styles.

---

# Workflow Example

Checkpoint Loader

↓

CLIP Text Encode

↓

Negative Prompt

↓

Empty Latent Image

↓

KSampler

↓

VAE Decode

↓

Save Image

---

# Best Practices

- Keep nodes organized.
- Label important nodes.
- Remove unused nodes.
- Save working workflows.

---

# Common Mistakes

- Broken connections.
- Wrong checkpoint selection.
- Missing VAE node.
- Forgetting Save Image.

---

# Next Step

Continue with **Workflows.md** to learn professional ComfyUI workflow design.
