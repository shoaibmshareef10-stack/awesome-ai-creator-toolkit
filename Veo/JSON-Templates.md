# Veo JSON Templates Guide

## Introduction

JSON templates provide a structured way to organize prompts for Veo. They improve consistency, make prompts reusable, and simplify complex video generation workflows.

---

# Basic JSON Template

```json
{
  "subject": "",
  "action": "",
  "environment": "",
  "camera": "",
  "lighting": "",
  "style": "",
  "quality": "8K"
}
```

---

# Character Template

```json
{
  "character": {
    "name": "",
    "age": "",
    "appearance": "",
    "outfit": "",
    "expression": ""
  }
}
```

---

# Camera Template

```json
{
  "camera": {
    "angle": "",
    "movement": "",
    "lens": "",
    "focus": ""
  }
}
```

---

# Environment Template

```json
{
  "environment": {
    "location": "",
    "time": "",
    "weather": "",
    "atmosphere": ""
  }
}
```

---

# Complete Prompt Template

```json
{
  "character": {
    "name": "Hero",
    "appearance": "Black futuristic suit"
  },
  "action": "Standing on a rooftop",
  "environment": {
    "location": "Cyberpunk city",
    "time": "Sunset",
    "weather": "Light rain"
  },
  "camera": {
    "angle": "Low Angle",
    "movement": "Dolly In",
    "lens": "50mm"
  },
  "lighting": "Golden Hour",
  "style": "Hollywood Cinematic",
  "quality": "Ultra Realistic 8K"
}
```

---

# Best Practices

- Keep JSON clean and valid.
- Use descriptive values.
- Reuse templates across projects.
- Maintain a consistent structure.
- Validate before use.

---

# Common Mistakes

- Missing commas
- Invalid quotes
- Empty required fields
- Inconsistent key names
- Incorrect nesting

---

# Pro Tips

- Save reusable templates.
- Build separate templates for different scene types.
- Keep character, camera, and environment in separate sections.
