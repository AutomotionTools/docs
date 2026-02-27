# How to Use MarkerMover

MarkerMover allows you to move, copy, paste and delete markers that are within your comp's work area.
You can adjust this work area to limit which markers are affected by the tool. It also provides an easy way
to trigger animation based on markers.

## Text Field

Enter the number of frames or seconds to move the affected markers.<br/>This accepts positive and negative values.

* **Alt-click:** Revert to default value of 1.

## Move Markers

* **Click:** Move markers by the specified amount.
* **Alt-click:** Multiply the text field's value by -1 before moving.
* **Shift-click:** Multiply the text field's value by 10 before moving.
* **Alt-Shift-click:** Multiply the text field's value by -10 before moving.

## Time Format toggle

Toggle this button to switch the unit reference between frames and seconds.

## Split Markers toggle

* When active, MarkerMover will affect the start and end points of a split marker independently.

    For example, if the start of a marker is outside of the work area and the end of the marker is within the work area, the duration of the marker will be changed.

* When inactive, only markers that start within the work area will be affected, and the end points of any split markers will move with the start of the marker.

## Include Protected Regions toggle

Toggle to include or exclude special 'Protected Region' comp markers.<br/>This also affects the Copy/Paste functions.

## Copy Markers

* **Click:** Copy markers that start within the work area to the script's clipboard from the active comp or selected layers.

* **Alt-click:** Cut markers instead of copy.

* **Shift-click:** Copy a single marker from the comp or top-most selected layer at the CTI.

    * With no layers selected, comp markers within range are copied.
    
    * When any number of layers are selected, all markers within range from each of those layers are copied.

## Paste Markers

* **Click:** Paste markers from the script's clipboard to the active comp or selected layers.

* **Alt-click:** Delete markers in the work area before pasting.

* **Ctrl-click:** Update markers from the layer's source (eg. from a pre-comp).

    * If two or more copied markers share the same start time, the top-most copied layer is pasted. If you paste onto a comp or layer that has a marker at the same start time as a copied marker, the existing marker will be overwritten.

    * With no layers selected, markers are pasted as comp markers.

    * When any number of layers are selected, all copied markers are pasted onto each layer.<br/>'Protected Region' comp markers will not be pasted onto layers.

## Paste to CTI toggle

* When active, the first copied marker will be pasted at the CTI.

* When inactive, the copied markers will be pasted at their original times.

## Work Area

* **Alt-click:** Save the current work area time and duration to the script's clipboard.

* **Click:** Apply the saved work area time and duration to the active comp.

* **Ctrl-click:** Update markers from source, on selected layers.

* **Shift-click:** Duplicate the comp markers onto a new 'dummy' layer at the top of the layer stack.<br/>(This enables you to use keyboard shortcuts to navigate through the comp markers.)

## Delete Markers

* **Click:** Remove all markers in work area from the active comp or selected layers.

* **Shift-click:** Remove all markers from the active comp or selected layers.

## Apply Marker Trigger Expression

Trigger animations on a property with markers. You can set a specific marker comment as a trigger, reference markers on other layers or the active comp, and adjust the timing of the animation.

[:material-arrow-right-box: **Read here for more information**](MarkerTrigger.md)

## Memory Banks

These five buttons allow you to save a marker (or set of markers) to each button, and to apply the saved markers to layers or comps. These saved markers are retained between After Effects sessions.

* **Click:** Apply a previously saved marker or set of markers.

* **Alt-click:** Save all markers that start within the work area to the Memory Bank, from the active comp or selected layers.

* **Shift-click:** Save a single marker from the comp or top-most selected layer, at the CTI to the Memory Bank.