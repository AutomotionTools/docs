# Polymorph

!!! note "User guide: Work in progress"

    This user guide is a work in progress. I'm trying to add to it as frequently as I'm able, in order to cover all of the features. If a feature is missing that you need information on, please feel free to [let me know](https://aescripts.com/contact/?direct=1&product_id=2287) and I can aim to prioritise that next.

**Polymorph allows you to replace any number of layers with the contents of another selected layer.<br/>Want to swap text for pre-comps, shape layers for video footage, or images for 3D objects? No problem!**

<video src="../assets/polymorph/Polymorph - Basketball Comparison - COMPRESSED.mp4" width="100%" autoplay loop></video>

Simply select your Source layer first, then any number of Target layers, then click the 'Polymorph' button.

There are a number of options available to control the properties and attributes that are inherited by the replacement layers.

## Why is this useful?

Many layer types can be replaced easily in After Effects by Alt-dragging onto the layer or the Project panel item. However, items that don't have sources – namely shape layers and text layers – can't be replaced in this way, and can't be used to replace other types of items.

**With Polymorph, any number of target layers can be replaced with the contents of a source layer, regardless of the layer type of the source or target layer.**

Additionally, transform properties and layer attributes can be applied to speed up layer replacement even further:

* With standard Alt-drag replacement, the target layers retain all of their existing properties. This means, for example, that if the replacement source is much larger than the original source, then all replacements will be oversized, and the user must go through and adjust the scale for each.

* With Polymorph, the source transform properties can (optionally) act as multipliers or additives – for example, if a source layer is set to 50% scale, and a target layer is set to 30% scale, the replacement layer will be set to 15% scale.

Furthermore, if a source layer is masked, there is no native way for that mask to carry across to Alt-dragged replacements. Polymorph is able to do this, as well as retain the source layer's track matte.

## Some use cases:

* Replace any number of shape layers with a replacement shape layer.

* Rapidly replace shape layers used in simulations, such as [**Newton**](https://aescripts.com/newton/){:target="_blank"}.

* Build a rig with shape layers for more responsive development, then replace those shape layers with final assets at completion – this works well in conjunction with [**RenderHogs**](https://aescripts.com/renderhogs/){:target="_blank"}.

* Or do that in reverse – is a heavy rig slowing down performance? Add in shape layer replacements for pre-comps and switch back and forth at will.

* Re-use character rigs by easily swapping out body parts, even if they're already animated. This works well with [**Limber**](https://aescripts.com/limber/){:target="_blank"} and [**RubberHose**](https://battleaxe.co/rubberhose){:target="_blank"}.

* Replace pre-rendered or raster text with live text, or vice versa.

* Replace shape layers sent over from [**Overlord**](https://battleaxe.co/overlord){:target="_blank"} with pre-comps – quickly layout in Illustrator, then use Polymorph to put assets into position.

* Attach layers to multiple existing layers, by retaining the visibility of targets and parenting duplicates to the targets.