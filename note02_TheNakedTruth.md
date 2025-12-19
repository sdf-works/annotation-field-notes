# The Naked Truth

A lot of multimodal annotation involves cropping an image and asking a model to regenerate what’s missing. Recently I ran into a model that, when you cropped a woman 
just above the shoulders, confidently regenerated the rest of her body completely naked.

From our side, this is a failure.
From the model’s side, it’s doing exactly what it learned.

And that’s the interesting part. If you train on the internet, on our content, our images, our patterns, what does it mean that “woman + cropped image” often maps 
to “naked body” in the model's statistical 'brain'?
It isn’t about the model being bad. It’s about the world it was trained on.

This kind of failure tells us something about model behavior, yes, but it tells us even more about the cultural dataset we’ve accidentally built for ourselves.
