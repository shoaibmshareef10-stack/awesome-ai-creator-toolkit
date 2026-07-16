# JSON Templates Guide

## Introduction

JSON templates help organize prompts in a structured way, making AI video generation more consistent and easier to reuse.

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

# Advanced JSON Template

```json
{
  "character": {
    "name": "",
    "age": "",
    "appearance": "",
    "outfit": ""
  },
  "scene": {
    "location": "",
    "weather": "",
    "time": ""
  },
  "camera": {
    "angle": "",
    "movement": "",
    "lens": ""
  },
  "lighting": {
    "type": "",
    "direction": "",
    "mood": ""
  },
  "audio": {
    "music": "",
    "effects": ""
  },
  "output": {
    "style": "Cinematic",
    "resolution": "8K",
    "aspect_ratio": "16:9"
  }
}
```

---

# Example

```json
{
  "subject": "Superhero",
  "action": "Standing on a rooftop",
  "environment": "Cyberpunk city at sunset",
  "camera": "Low-angle dolly in",
  "lighting": "Golden hour with volumetric fog",
  "style": "Hollywood blockbuster",
  "quality": "Ultra realistic 8K"
}
```

---

# Best Practices

- Use clear key names.
- Keep values descriptive.
- Reuse templates for consistency.
- Validate JSON before using it.
- Avoid unnecessary fields.

---

# Common Mistakes

- Missing commas
- Invalid quotes
- Empty required fields
- Inconsistent formatting

---

# Pro Tips

- Save reusable templates.
- Create different templates for different scene types.
- Maintain the same structure across projects.
