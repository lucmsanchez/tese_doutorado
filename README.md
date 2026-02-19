# Neuroimaging Results Viewer

This is a simple web-based viewer for NIfTI files (`.nii`, `.nii.gz`) powered by [NiiVue](https://github.com/niivue/niivue).

## How to Use

1.  **Open the Viewer**: Open `results.html` in a modern web browser (Chrome, Firefox, Edge).
    *   Note: You need an internet connection to load the NiiVue library.
2.  **Load Images**:
    *   Click "Choose Files" to select NIfTI files from your computer.
    *   Or simply **drag and drop** files directly onto the viewer.
3.  **Controls**:
    *   **Color Map**: Change the color scheme using the dropdown menu.
    *   **Radiological**: Toggle radiological convention (Left is Right).
    *   **Mouse Controls**:
        *   Left Click + Drag: Adjust contrast/brightness (on 2D slices) or rotate (on 3D render).
        *   Right Click + Drag: Zoom.
        *   Middle Click + Drag: Pan.
        *   Scroll: Change slice.

## Requirements

*   Web Browser with WebGL 2.0 support.
*   Internet connection (for loading NiiVue from CDN).