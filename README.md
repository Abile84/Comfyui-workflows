# FLUX 1.D — T2IMG / IMG2IMG Workflow for ComfyUI

A modular **ComfyUI workflow** designed for flexible **text-to-image** and **image-to-image** generation using **FLUX** and **LoRA** models.  
The setup integrates **advanced sampler controls**, **metadata saving**, **conditioning management**, and **Florence 2 model support**.

---

## 🧩 Features

- ✅ Dual text encoding with **CLIP + T5**
- ✅ Support for **LoRA** (MODEL + CLIP)
- ✅ **Text-to-Image** and **Image-to-Image** workflows combined
- ✅ Advanced control over:
  - Sampler / Scheduler
  - CFG Scale, Steps, Seed
  - Width & Height
- ✅ Metadata saving with full generation parameters
- ✅ Integration with **Florence 2** model loader
- ✅ Preconnected nodes for clean extension or modification

---

## ⚙️ Requirements

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- Installed custom nodes:
  - `comfyui-kjnodes`
  - `comfyui-image-saver`
  - `comfyui-florence2`
  - `comfy-core`

---
