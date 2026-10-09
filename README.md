# Photoshop Object Isolator

A Photoshop script (`.jsx`) that helps isolate objects from backgrounds (such as plain white/black backgrounds) or extracts objects that have a distinct color from their background.

## Features
- Interactive Levels refinement to crunch black/white points for the perfect mask.
- Allows you to isolate based on Grayscale, Red, Green, or Blue channels to find the highest contrast.
- Can process an initial Lasso selection so you can spatially isolate objects before contrast isolation.
- Finishes by leaving a live selection (marching ants) around your object, so you can easily click the "Add Layer Mask" button in Photoshop to remove the background.

## Installation
1. Download `Object_Isolator.jsx`.
2. Place it in your Photoshop scripts folder (e.g., `C:\Program Files\Adobe\Adobe Photoshop [Version]\Presets\Scripts`).
3. Restart Photoshop. The script will be available under `File > Scripts > Object_Isolator`.
