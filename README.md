# TinyTweener for Unity
I wrote this class because i needed something like iTween or DOTween
but without installing any external library for my project. I call it
"one class for everything". Well not "everything" but you get the point.
TinyTweener it's a quick and fast general utility to move objects and
change values with zero floating point errors. It also offer many options
of use for different conditions.

# MoveTo()
Move a transform from Vector3 postion A to Vector3 position B, and rotate forward to each position.

# RotateTo()
Rotate a transform from a Quaternion A to a Quaternion B.

# ScaleTo()
Locally scale a transform.

# ColorTo()
Transition colors.

# LightColorTo()
Change color of a light.

# LightIntensityTo()
Change the intensity of a light.

# AudioFadeTo()
Fade the volume of an AudioSource from actual to desired.

# ImageFillAmount()
Change the fill parameter of an Image component.

# ImageFade()
Change the color alpha channel of an Image component. Can be useful in VR applications to fade the screen
to black when players try to sneak through the walls.

# Example of usage.

Attach it to a GameObject, reference it and call the function fron any script.
```
MoveTo(this.transform, _target.transform.position, _target.transform.rotation, 10f);
```

Don't forget to use the namespace:
```
using LS;
```
