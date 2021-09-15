# Lecture 3: VR Development in Unity

Detailed explanation of this code can be found in the [lecture video](https://mediaspace.umn.edu/media/t/1_gpale6sr).

## Topics

1. Overview of the Oculus Quest
2. Creating a Unity project
3. Anatomy of a Unity project
4. Configuring the project
5. Overview of the Unity editor
6. Building to the Quest
7. Using Oculus Link with the Unity editor
8. Adding objects to the scene
9. Adding a C# script to an object

## Notes

1. The Android build error I encountered during class was the result of an update that did not get installed correctly on my laptop.  This is unrelated to GitHub.
2. Because of this error, there was one step we were not able to show in the video.  In the default scene, the controllers may not be visible when you first open the application on the headset.  (They will actually appear under the floor.)  This is because the tracking origin is set incorrectly.  To fix this, click on the XRRig object in the sample scene.  In the object inspector, change "Requested Tracking Mode" from Default to Floor.  This will place the origin at the floor level reported by the headset guardian system, so the controllers and headset will show up at the correct height.

## Participation Exercise

The participation exercise for this lecture is posted on Canvas.

## License

Material for [CSCI 5619 Fall 2021](https://canvas.umn.edu/courses/268490) by [Evan Suma Rosenberg](https://illusioneering.umn.edu/) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

The intent of choosing CC BY-NC-SA 4.0 is to allow individuals and instructors at non-profit entities to use this content.  This includes not-for-profit schools (K-12 and post-secondary). For-profit entities (or people creating courses for those sites) may not use this content without permission (this includes, but is not limited to, for-profit schools and universities and commercial education sites such as Coursera, Udacity, LinkedIn Learning, and other similar sites).   

