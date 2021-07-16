---
sidebar_position: 3
---

# Cleaning Speech Bubbles

## Using cleaning mode

Cleaning is the stage of scanlation where the original text from the image is removed. Autocomic facilitates this process by intelligently suggesting regions of the the image containing speech bubbles. All of the selected text can be subsequently removed in a single click.

To enter the cleaning mode,
1. Open your project from the `My Works` tab
2. Select `cleaning` mode from the dropdown in the top bar


## Introduction to suggested masks

When an image is loaded, Autocomic automatically generates a mask of the regions of the page containing speech bubbles.

These suggestions can be regenerated at any time by clicking on the `Regenerate` button–highlighted in red–in the toolbar. Try it below!

<div style={{position:"relative", "padding-bottom": "56.25%"}}>
    <iframe frameborder="0" style={{border: "1px solid rgba(0, 0, 0, 0.1)", position: "absolute", left:0, top:0}} width="100%" height="100%" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FVMoeNdQpt5F0J7yfq1MfJ9%2FUI%3Fnode-id%3D10%253A13%26scaling%3Dscale-down-width%26page-id%3D0%253A1%26starting-point-node-id%3D10%253A13%26hide-ui=1" allowfullscreen></iframe>
</div>

## Modifying suggested masks

Sometimes Autocomic's suggested masks are inaccurate.

To expand a mask to include more of the image
1. Ensure that `cleaning` mode is selected from the dropdown in the top bar
2. Click on the `Brush Tool` in the toolbar
3. Select the correct mask layer from the `Layers` dialog on the right side
:::info
If a new mask is to be created, do not select a layer.
:::
4. Use the brush to draw over any regions of the image that should be included in the mask

To remove parts of the mask
1. Ensure that `cleaning` mode is selected from the dropdown in the top bar
2. Click on the `Erase Tool` in the toolbar
3. Select the correct mask layer from the `Layers` dialog on the right side
4. Use the eraser over any regions of the image to remove from the mask

## Previewing results
You can toggle between editing bubble masks and viewing a preview of the cleaned result by pressing the eye button at the bottom right of the page.