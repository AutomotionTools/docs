# How to Use Loopy

Loopy can be used to loop almost anything within After Effects.

Select the properties and/or layers that you want to loop, and press one of the four Loop buttons to apply a loop to these (*Continue*, *Ping pong*, *Offset* or *Continue* loop types). Loop expressions can be applied to multiple selected layers and/or properties at the same time.

!!! note "Note"

    Some properties and effects don't support all loop types.

## Looping paths and masks

The native `loopIn()` and `loopOut()` expressions do not work when applied to shape or mask paths. When one of these properties is selected, Loopy detects this and automatically applies a custom loop expression instead.

The Loop Direction button toggles between 'Loop In', 'Loop Out', and both 'Loop In' and 'Loop Out' together.

## Looping audio-visual layers and pre-comps

When an AV layer or pre-comp is selected, without selecting any properties on that layer, Loopy will apply Time Remap, place keyframes at the trimmed In and Out point, and loop this property. (If the layer does not support Time Remap, the layer will be skipped, with a warning shown.)

If the Time Remap property is already active and has an expression applied, Loopy will only replace the expression, without modifying keyframes.

Alt/Option-clicking the '*Cycle Loop*' button will apply Time Remap and place keyframes at the trimmed In and Out points, but will not apply any expressions. If the Time Remap property is already active, the layer will be unaffected.

## Loop direction

The '*Loop Direction*' button toggles between 'Loop In' (loop before any keyframes), 'Loop Out' (loop after any keyframes), and both 'Loop In' and 'Loop Out' together (loop before and after any keyframes).

## Keyframe modifier

The Set Keyframe Modifier field limits the loop behaviour to a specific number of keyframes (layer selections will be ignored). Alt-click this field to revert to its default value of 0.

The Keyframe Modifier toggle ensures that the Keyframe Modifier value doesn't exceed the number of existing keyframes.

!!! note "Note"

    The '*Continue*' loop type doesn't support the keyframe modifier parameter.

## Keep expressions

The Keep Expressions toggle will comment out and retain any existing expression on a property.