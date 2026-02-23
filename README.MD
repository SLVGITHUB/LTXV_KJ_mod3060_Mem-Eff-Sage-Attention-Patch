# 🔧 KJ Nodes - Sage Attention Mode Activation Guide on RTX30XX Videocards

<div align="center">
  
### *Enable Sage Attention mode in KJ: LTX2 Mem Eff Sage Attention Patch*

If you are experiencing a drop when processing VAE tiled and any decoding on the RTX30XX video processor, use this notch instead of the LTX2 Mem Eff Sage Attention Patch from KJ if it does not work for you

[![ComfyUI](https://img.shields.io/badge/ComfyUI-Custom_Node-orange)](https://github.com/comfyanonymous/ComfyUI)
[![Version](https://img.shields.io/badge/Version-1.0-blue)]()
[![Windows](https://img.shields.io/badge/Platform-Windows-0078D6)]()

</div>

---

## 📋 Overview

This guide walks you through the process of replacing the node file to activate the **Sage Attention mode** in the KJ: LTX2 Mem Eff Sage Attention Patch.

---

## ⚙️ Step-by-Step Instructions

### 📂 1. Navigate to the Nodes Directory

**Option A - Using File Explorer:**

---

## 📁 File Structure Reference

```
C:\ComfyUI
├── custom_nodes
│   └── comfyui-kjnodes
│       └── nodes
│           ├── ltxv_nodes.py        ← New file
│           ├── ltxv_nodes_backup.py  ← Your backup
│           └── [other node files]
```

---

## ✅ Verification

After replacement, restart ComfyUI and verify that:
- The node appears in your node list
- Sage Attention mode is available in the node settings

---

## ⚠️ Important Notes

- 🚫 Do **NOT** skip the backup step
- 🔍 Ensure you're in the correct directory before replacement
- 🔄 Restart ComfyUI after file replacement

---

## 🆘 Troubleshooting

If you encounter issues:
1. Check that the file name is exactly `ltxv_nodes.py`
2. Verify you're in the right directory
3. Restore from backup if needed

---

<div align="center">
  
**Made with ⚡ for ComfyUI users**

</div>
```

This README features:
- Clear visual hierarchy with emoji icons
- Step-by-step instructions with code blocks
- Visual file structure diagram
- Warning highlights
- Verification steps
- Troubleshooting section
- Professional formatting with badges and dividers
