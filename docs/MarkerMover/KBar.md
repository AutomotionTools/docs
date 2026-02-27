# Using MarkerMover with KBar

MarkerMover is configured for use with KBar — simply change the ‘Script function or argument’ value (see screenshot below) to change the function of the KBar button. You will need to relink the script file field to point to the installed `MarkerMover.jsxbin` file. There are provided icons for each of these functions.

If you are using KBar3, there is a `.kbar` file included for easy import of the toolbar buttons.

![Screenshot of a KBar settings panel](../assets/markermover/MarkerMover%20-%20KBar%20Panel.png){ width="600" }

| | Script argument | Function |
| --- | ----------- | ----------- |
| ![Icon for MarkerMover panel](../assets/markermover/kbar-icons/markermover.png){width="32"} | (None) | Open MarkerMover panel |
| ![Icon for 'Move with Prompt'](../assets/markermover/kbar-icons/move-prompt.png){width="32"} | move-prompt | Opens a prompt, into which you can type a value. Markers within the work area are moved by this amount. The *Time Format*, *Split Markers* and *Protected Region Marker* toggles all affect this behaviour. |
| ![Icon for 'Move'](../assets/markermover/kbar-icons/move.png){width="32"} | move | Moves the applicable markers by the last used value. Behaviour is affected as above. |
| ![Icon for 'Move Reverse'](../assets/markermover/kbar-icons/move-reverse.png){width="32"} | move-reverse | As above, but it will apply a negative of the last used value. Behaviour is affected as above. |
| ![Icon for 'Toggle Time Format'](../assets/markermover/kbar-icons/toggle-time-format.png){width="32"} | toggle-time-format | Toggles the time format between frames and seconds. |
| ![Icon for 'Toggle Split Markers'](../assets/markermover/kbar-icons/toggle-split-markers.png){width="32"} | toggle-split-markers | Toggles the split markers control. |
| ![Icon for 'Toggle Protected Markers'](../assets/markermover/kbar-icons/toggle-time-format.png){width="32"} | <span class="nowrap">toggle-protected-markers</span> | Toggles the protected markers control. |
| ![Icon for 'Copy'](../assets/markermover/kbar-icons/copy.png){width="32"} | copy | Copy markers within the work area from selected layers (or comp, if no layers are selected). This is the same as clicking the copy button in the script panel. |
| ![Icon for 'Cut'](../assets/markermover/kbar-icons/cut.png){width="32"} | cut | As above, but deletes copied markers. |
| ![Icon for 'Copy Single'](../assets/markermover/kbar-icons/copy-single.png){width="32"} | copy-single | Copy a single marker at the CTI. This is the same as shift-clicking the copy button in the script panel. |
| ![Icon for 'Paste'](../assets/markermover/kbar-icons/paste.png){width="32"} | paste | Pastes copied markers to  selected layers (or comp, if no layers are selected). This is the same as clicking the paste button in the script panel. |
| ![Icon for 'Paste Overwrite'](../assets/markermover/kbar-icons/paste-overwrite.png){width="32"} | paste-overwrite | As above, but markers on selected layers (or comp, if no layers are selected) within the work area are deleted before markers are pasted. |
| ![Icon for 'Delete'](../assets/markermover/kbar-icons/delete.png){width="32"} | delete | Deletes all markers within the work area from selected layers (or comp, if no layers are selected). |
| ![Icon for 'Delete All'](../assets/markermover/kbar-icons/delete-all.png){width="32"} | delete-all | Deletes all markers from selected layers (or comp, if no layers are selected). |
| ![Icon for 'Toggle CTI'](../assets/markermover/kbar-icons/toggle-cti.png){width="32"} | toggle-cti | Toggles the *Paste first marker to CTI* control. |
| ![Icon for 'Work Area Save'](../assets/markermover/kbar-icons/workarea-save.png){width="32"} | workarea-save | Saves the current work area settings. |
| ![Icon for 'Work Area Apply'](../assets/markermover/kbar-icons/workarea-apply.png){width="32"} | workarea-apply | Applies the saved work area settings to the active comp. |
| ![Icon for 'Update Markers'](../assets/markermover/kbar-icons/update-markers.png){width="32"} | update-markers | Triggers the native *Update markers from source* function. |
| ![Icon for 'Comp Markers'](../assets/markermover/kbar-icons/comp-markers.png){width="32"} | comp-markers | Duplicates all comp markers onto a new 'dummy' layer. If this 'dummy' layer already exists in the comp, then its markers are removed and updated with the current comp markers. |
| ![Icon for 'Trigger'](../assets/markermover/kbar-icons/trigger.png){width="32"} | trigger | Open the Marker Trigger interface. This is the same as clicking the *Apply marker trigger expression to selected properties* button in the script panel. |
| ![Icon for 'Memory Bank Copy'](../assets/markermover/kbar-icons/memorybank1-copy.png){width="32"} | memorybank1-copy<br />memorybank2-copy<br />memorybank3-copy<br />memorybank4-copy<br />memorybank5-copy | Saves markers in the work area to Memory Banks 1–5. |
| ![Icon for 'Memory Bank Copy Single'](../assets/markermover/kbar-icons/memorybank1-copy-single.png){width="32"} | <span class="nowrap">memorybank1-copy-single</span><br /><span class="nowrap">memorybank2-copy-single</span><br /><span class="nowrap">memorybank3-copy-single</span><br /><span class="nowrap">memorybank4-copy-single</span><br /><span class="nowrap">memorybank5-copy-single</span> | Saves a single marker to Memory Banks 1–5. |
| ![Icon for 'Memory Bank Paste'](../assets/markermover/kbar-icons/memorybank1-paste.png){width="32"} | memorybank1-paste<br />memorybank2-paste<br />memorybank3-paste<br />memorybank4-paste<br />memorybank5-paste | Pastes the marker(s) stored in Memory Banks 1–5. |