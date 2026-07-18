# ComfyUI Ultimate Guide

## Introduction

This guide combines everything you need to master ComfyUI. By following this workflow, you can create professional AI images with complete control over models, prompts, nodes, and workflows.

---

# Step 1: Plan Your Project

Before building a workflow, decide:

- What image do you want to create?
- Which AI model will you use?
- Do you need ControlNet or LoRA?
- What quality level is required?

---

# Step 2: Build the Workflow

Basic workflow:

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

# Step 3: Write Better Prompts

Use this formula:

Subject → Action → Environment → Lighting → Camera Angle → Style → Quality

### Example

A futuristic female warrior standing in a neon cyberpunk city, cinematic lighting, volumetric light rays, low-angle shot, ultra realistic, highly detailed, 8K.

---

# Step 4: Choose the Right Models

Recommended model types:

- Checkpoints
- VAE
- LoRA
- ControlNet
- Upscaler Models

Use compatible versions for the best results.

---

# Step 5: Optimize Performance

- Keep workflows simple.
- Remove unused nodes.
- Use reusable templates.
- Generate previews before final renders.
- Save stable workflow versions.

---

# Step 6: Organize Projects

- Create folders for workflows.
- Organize models by category.
- Keep backups.
- Label important workflows clearly.

---

# Step 7: Review Before Rendering

Check:

- Node connections
- Prompt quality
- Model compatibility
- Lighting
- Composition
- Output settings

---

# Common Mistakes

- Incorrect node connections
- Incompatible models
- Weak prompts
- Overly complex workflows
- Forgetting to save workflows

---

# Pro Tips

- Build a workflow library.
- Learn keyboard shortcuts.
- Keep ComfyUI and extensions updated.
- Experiment with different samplers.
- Practice creating reusable templates.

---

# Complete Workflow

1. Plan the project.
2. Select the model.
3. Build the workflow.
4. Write the prompt.
5. Configure parameters.
6. Generate preview images.
7. Refine the workflow.
8. Render the final image.
9. Save the workflow and output.

---

# Congratulations!

You have completed the ComfyUI Guide. You now have a complete reference for building powerful, flexible, and professional AI image generation workflows.
