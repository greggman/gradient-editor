Gradient Editor
===============

A gradient editor in jQuery

PLEASE CONTRIBUTE!!!

I don't know jQuery and my CSS skills suck so I could
really use some help / advice on best practices.


Demo
----

[http://greggman.github.com/gradient-editor/](http://greggman.github.com/gradient-editor/)

Goals
-----

The goal here is to make a gradient editor that can be used to edit both CSS gradients
and more importantly for me, give me data that I can use to generate gradients using
canvas 2d.

See [issue tracker](https://github.com/greggman/gradient-editor/issues).

Why?
----

For me the biggest reason is because ramp textures are super important for 3D graphics
and now that WebGL makes them accessible to anyone we need a ramp editor to let people
play with ramp textures.

Examples:

* Typical lighting comes up with a multiplier from 0.0 to 1.0 usually based on the
angle of the viewer to the surface vs the angle light to the surface. Instead of
using that number directly, use it as a lookup into a ramp texture for much finer
control. From just adjusting how the lighting looks in general to making interesting
toon shaders you can do it all with a ramp texture. 
[See this work-in-progress demo](http://webglsamples.googlecode.com/hg/toon-shading/toon-shading.html)

* Similarly, instead of having light color be a constant use another ramp texture
to have things in the back lit differently than things in the front.

* Ramp textures can be used to color particles over time. Pass in the time, use
the time to lookup a color in the ramp texture.





