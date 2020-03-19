# WebGLDomInteraction

An example of how the DOM interaction can be used to influence a WEBGL render.
The example is also programmed to use a software renderer as a fall back to WEBGL and hardware acceleration. 
The two libraries CanvasRenderer and Projector achieve this. There is also some minimal logic in the WEBGL controller to apply its use.

# Get Started

Simply open index.html in a browser that supports WEBGL and drag drop the shapes onto the render area. (Does not need to be run from a server).

# Why?

Back in 2016 I needed to look into whether a WEBGL using a canvas as a viewport could be influenced by DOM interactions, especially dragging items from the DOM. Therefore I did a quick spike to illustrate it was possible.
