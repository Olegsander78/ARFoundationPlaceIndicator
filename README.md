# ARFoundationPlaceIndicator

This is a template project for Unity's AR Foundation system. It's ready to build and includes an AR placement indicator. This is a reticle that tracks the center of your screen in the AR world. So it snaps to surfaces such as tables, the floor, walls, etc. It can be used to spawn in objects, or any other feature you wish to include in your AR app.
What is AR Foundation?

Right now, there are two main AR SDK's available. ARCore for Android and ARKit for iOS. AR Foundation is an API which allows the developer to create AR apps for both platforms seamlessly. Developers don't need to create separate projects for Android and iOS, or have even more convoluted code. It's all packaged into one with AR Foundation.

So what can we do with AR Foundation?

    Detect surfaces
    Identify feature points in the world
    Track virtual objects in the real world
    Adjust the lighting in Unity based on a real world estimate
    Face, image and object tracking
    Unity documentation

### Demo Scene

AR Session: runs and manages the current AR session.

AR Session Origin: defines the center of the AR session. Also includes a few other components that we need: AR Raycast Manager, AR Plane Manager.

AR Camera: renders the device camera and AR objects.

PlacementIndicator: AR reticle which snaps to the tracked surfaces.
