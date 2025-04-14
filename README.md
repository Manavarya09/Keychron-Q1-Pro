# Keychron Q1 Pro - Custom QMK Keymap

This is a custom QMK keymap for the **Keychron Q1 Pro (ANSI layout)** with support for:

- RGB Matrix
- Rotary Encoder (default: volume control)
- Layer switching (Layer 1 via `MO(1)`)

## 📁 Folder Structure

Place this folder inside the QMK repository at:
```
keyboards/keychron/q1_pro/keymaps/custom/
```

## 🧠 Layers

### Layer 0 - Default
Standard ANSI layout with RGB and encoder enabled.

### Layer 1 - FN Layer
Currently all keys are transparent (`_______`). Customize as needed.

## 🎛️ Encoder Behavior

Rotary encoder (index 0):
- Clockwise: Volume Up
- Counter-clockwise: Volume Down

## 🌈 RGB

RGB Matrix is enabled by default. You can customize lighting effects in QMK.

## 🔧 Compile Firmware

Run this from the QMK root:
```sh
qmk compile -kb keychron/q1_pro -km custom
```

## 🚀 Flash Firmware

Put your board into DFU mode and run:
```sh
qmk flash -kb keychron/q1_pro -km custom
```

---

Made with ❤️ using QMK Firmware  
[https://qmk.fm](https://qmk.fm)
