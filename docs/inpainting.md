---
sidebar_position: 3
---

# Using inpainting mode

Inpainting is the stage of scanlation where the original text outside of speech bubbles from the background are removed.
Autocomic allows you to select regions where text may be overlapping with the background, and then automatically re-draws the background.


To enter the inpainting mode,
1. Open your project from the `My Works` tab
2. Select `inpainting` mode from the dropdown in the top bar


## Inpaint parts of the image

To inpaint a part of the image: 
1. Ensure that the `inpainting` mode is selected from the dropdown in the top bar
2. Click the `Brush Tool` in the toolbar
3. Select the correct mask layer from the `Layers` dialog on the right side
:::info
If a new mask is to be created, do not select a layer.
:::
4. Use the brush to draw over any regions of the image that should be included in the mask
5. The selected region will automatically be erased and redrawn to fit with the surrounding scenery

To remove parts of the mask
1. Ensure that the `inpainting` mode is selected from the dropdown in the top bar
2. Click on the `Erase Tool` in the toolbar
3. Select the correct mask layer from the `Layers` dialog on the right side
4. Use the eraser over any regions of the image to remove from the mask

<div style={{position:"relative", "padding-bottom": "56.25%"}}>
    <iframe frameborder="0" style={{border: "1px solid rgba(0, 0, 0, 0.1)", position: "absolute", left:0, top:0}} width="100%" height="100%" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FVMoeNdQpt5F0J7yfq1MfJ9%2FUI%3Fnode-id%3D271%253A62%26scaling%3Dscale-down-width%26page-id%3D0%253A1%26starting-point-node-id%3D271%253A62%26hide-ui=1" allowfullscreen></iframe>
</div>

## Preview results of the inpainting

To view the results of the automatic inpainting:
1. Ensure that the `inpainting` mode is selected from the dropdown in the top bar
2. Press the eye button at the bottom right of the page to preview the inpainted result
