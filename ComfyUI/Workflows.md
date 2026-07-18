# ComfyUI Workflows Guide

## Introduction

A workflow in ComfyUI is a connected graph of nodes that generates, edits, or enhances images. Well-designed workflows improve efficiency, consistency, and image quality.

---

# Basic Workflow

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

# Image-to-Image Workflow

- Load Image
- VAE Encode
- CLIP Text Encode
- KSampler
- VAE Decode
- Save Image

Use this workflow to transform or improve existing images.

---

# Inpainting Workflow

- Load Image
- Load Mask
- Inpaint Model
- KSampler
- VAE Decode
- Save Image

Perfect for removing or replacing parts of an image.

---

# Upscaling Workflow

- Load Image
- Upscale Model
- Image Upscaler
- Save Image

Used to increase image resolution while preserving details.

---

# ControlNet Workflow

- Load Control Image
- ControlNet
- CLIP Text Encode
- KSampler
- Save Image

Provides better control over poses, edges, and composition.

---

# Best Practices

- Keep workflows clean and organized.
- Group related nodes together.
- Label important sections.
- Save reusable workflow templates.
- Test one change at a time.

---

# Common Mistakes

- Unnecessary nodes.
- Incorrect node connections.
- Mixing incompatible models.
- Forgetting to save workflows.

---

# Pro Tips

- Create reusable templates.
- Organize workflows by project.
- Keep backup copies.
- Optimize complex graphs gradually.

---

# Next Step

Continue with **Models.md** to learn how to manage AI models in ComfyUI.
