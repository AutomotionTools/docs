# How to Use Random Roller

Random Roller allows you to select a random subset of selected layers, sort a selection of layers randomly into groups, or rearrange selected layers into a random order.

<div>
  <div style="position:relative;padding-top:56.25%;">
    <iframe src="https://www.youtube.com/embed/p-I5bgtZY-E" frameborder="0" allowfullscreen
      style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe>
  </div>
</div>

----------

## Random layer selection

![Screen recording of random layer selection](https://docassets.rob-barrett.com/random-roller/Random Layer Selection - v01.gif){ width="500" }

Assign a selected or deselected status to each selected layer at random. Pressing this button an additional time will create a subset selection of those layers selected in the previous step.

## Re-roll random selection

![Screen recording of re-rolling random layer selection](https://docassets.rob-barrett.com/random-roller/Re-roll Random Selection - v01.gif){ width="500" }

![Screen recording of re-rolling random group selection](https://docassets.rob-barrett.com/random-roller/Re-roll Random Groups - v01.gif){ width="500" }

* **Layers:** If the previous randomization was created by the 'Random Layer Selection' button, this will re-randomize your previous layer selection.
* **Groups:** If the previous randomization was created by the 'Randomize Layers into X Groups' button, this will re-randomize the groups to which those layers are assigned.

## Invert random selection

![Screen recording of inverting random layer selection](https://docassets.rob-barrett.com/random-roller/Invert Random Selection - v01.gif){ width="500" }

![Screen recording of inverting random group selection](https://docassets.rob-barrett.com/random-roller/Invert Group Selection - v01.gif){ width="500" }

* **Layers:** If the previous randomization was created by the 'Random Layer Selection' button, this will swap the enabled/disabled status of all layers from your initial selection.
* **Groups:** If the previous randomization was created by the 'Randomize Layers into X Groups' button, this will swap the enabled/disabled status of all selected grouped layers.

## Random layer order / Random selection order

![Screen recording of rearranging layers into a random order](https://docassets.rob-barrett.com/random-roller/Random Layer Order - v01.gif){ width="500" }

![Screen recording of re-selecting layers in a random selection](https://docassets.rob-barrett.com/random-roller/Random Selection Order - Layers - v01.gif){ width="500" }<br />![Screen recording of re-selecting layers in a random selection, with keyframes selected](https://docassets.rob-barrett.com/random-roller/Random Selection Order - Keyframes - v01.gif){ width="500" }

* Rearrange the selected layers into a random order.
* **Alt-click:** Re-select the selected layers in a random order. This is helpful when using the [Quick Offset](https://helpx.adobe.com/after-effects/using/selecting-arranging-layers.html#quick-offset) feature of After Effects.

## Randomize layers into X groups

![Screen recording of randomising selected layers into a specified number of groups](https://docassets.rob-barrett.com/random-roller/Randomize Layers into X Groups - v01.gif){ width="500" }

Sort the selected layers into a specified number of groups.

## Select Group X

![Screen recording of selecting a previously randomised group](https://docassets.rob-barrett.com/random-roller/Select Group X - v01.gif){ width="500" }

Select all layers from the specified group. Any other layers in the comp will be deselected.

## Add Group X to selection

![Screen recording of adding a previously randomised group to the current selection](https://docassets.rob-barrett.com/random-roller/Add Group X to Selection - v01.gif){ width="500" }

Adds all layers from the specified group to the current layer selection.

----------

## Options

![Screenshot of group identifiers added to layers](https://docassets.rob-barrett.com/random-roller/Group Options.png){ width="500" }

When randomizing layers into groups, Random Roller will add a Slider Control effect to each layer (if it's a layer type that supports sliders) to indicate the group to which it has been assigned.

You can also choose to:

* Change the label color of each layer to match the group to which it has been assigned. If you specify more than 16 groups, then the label color assignment will loop around (i.e. Group 17 will have the same label color as Group 1).
* Prefix the layer name with the group number to which it has been assigned. This is recommended when you have layers, such as cameras and lights, that do not support effects.
* Append the group number to the layer comment. This is required if you would like the option of undoing the group randomization later, as it allows Random Roller to identify which layers were assigned to which groups.

These options can help you to keep track of which group each layer has been assigned to, and to reference them with expressions.