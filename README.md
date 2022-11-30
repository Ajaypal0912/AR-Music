# AR-Music

AR-Music is an Augmented Reality based project.

Virtual Reality- It's like creating a whole new virtual environment in a frame.

Augmented Reality- Augmented reality is adding virtual objects in a real environment.

Objective: implementing Augmented Reality for displaying images and controlling music through certain specified markers.

Scope: A major target was to build a model that can help children to learn things through images as learning by using images is more fascinating and fruitful. Along with images including music with all those images and controlling them will enhace the objective of the model designed for making learning process easy for children.


![image](https://user-images.githubusercontent.com/95572175/204848426-3bd5baa5-0c01-4c9f-bf74-02d12e1d5e01.png)

                         UseCase diagram for AR Model
                         
Implementation: Majorly while implementing the whole model i have used A-frame, Ar.js and howler.js libraries.

A-Frame- A-Frame is a web framework for building virtual reality (VR) experiences. A-Frame is based on top of HTML, making it simple to get started.

Originally conceived within Mozilla and now maintained by the co-creators of A-Frame within Supermedium, A-Frame was developed to be an easy yet powerful way to develop VR content. As an independent open source project, A-Frame has grown to be one of the largest VR communities.

A-Frame supports most VR headsets such as Vive, Rift, Windows Mixed Reality, Daydream, GearVR, Cardboard, Oculus Go, and can even be used for augmented reality. Although A-Frame supports the whole spectrum, A-Frame aims to define fully immersive interactive VR experiences that go beyond basic 360° content, making full use of positional tracking and controllers.

Ar.js- AR.js is a lightweight library for Augmented Reality on the Web, which includes features like Image Tracking, Location based AR and Marker tracking.\

AR.js features the following types of Augmented Reality, on the Web:

Image Tracking, when a 2D images is found by the camera, it's possible to show some kind of content on top of it, or near it.

Location Based AR, this kind of AR uses real-world places in order to show Augmented Reality content, on the user device. The experiences that can be built with this library are those that use a user's position in the real world.

Marker Tracking, When a marker is found by the camera, it's possible to show some content (same as Image Tracking). Markers are very stable but limited in shape, color and size.

Howler.js- howler.js is an audio library for the modern web. It defaults to Web Audio API and falls back to HTML5 Audio. This makes working with audio in JavaScript easy and reliable across all platforms.

Code: tag is used to create a scene using A-Frame library. A scene is the place where everything happens. When creating new objects in the demo, we will be adding them all to the scene to make them visible on the screen. In A-Frame, the scene is represented by a Scene entity.

Then to implement Augmented Reality, ar.js library is embedded in the tag using,

Now to select the animations that we want to show in the screen are selected and assests are created out from those animations using tag.

Then markers are need to be introduces using tag.

Used to add camera to the web browser.

To control the music the code used is:
<script>

		var drums = new Howl({
		
			src: ['./audio/drums.mp3']
			
		});
		
    </script>
