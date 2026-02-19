# NeuroImagine - Advanced NiiVue Viewer

A professional-grade, web-based viewer for neuroimaging data (NIfTI), powered by [NiiVue](https://github.com/niivue/niivue).

## Features

- **Multi-Format Support**: Load `.nii`, `.nii.gz` files.
- **Advanced Visualization**:
    - Multi-planar reconstruction (Axial, Coronal, Sagittal).
    - 3D Volume Rendering.
    - Adjustable slicing layouts.
- **Overlay Support**: Load multiple images on top of each other (e.g., statistical maps over structural MRI).
- **Customization**:
    - Multiple color maps (Jet, Viridis, Magma, etc.).
    - Toggle Crosshairs and Orientation text.
    - Radiological Convention support.
- **Tools**:
    - Screenshot capture.
    - Drag & Drop interface.

## Quick Start

1.  **Open** `results.html` in your web browser (Chrome/Edge/Firefox).
2.  **Load Data**:
    - Click **📁 Open File** button in the top toolbar.
    - Or **Drag & Drop** files directly into the window.
3.  **Add Overlays**:
    - Click **➕ Add Overlay** to layer additional maps.
4.  **Navigate**:
    - Use the **View** dropdown to switch between 2D slices and 3D render.
    - **Left Click + Drag**: Adjust contrast/brightness (2D) or Rotate (3D).
    - **Right Click + Drag**: Zoom.
    - **Middle Click + Drag**: Pan.
    - **Scroll**: Change slice.

## Requirements

*   Modern Web Browser with WebGL 2.0.
*   Internet Connection (loads NiiVue from CDN).