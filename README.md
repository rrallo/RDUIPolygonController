RDUIPolygonController
=========================

This is an iOS (and eventually android) UIController to all the user to switch between different modes via having a selector at the corners of a predefined shape. This is basically an alternative to the popular iOS UISegmentedController, with a much more graphical layout.

The main point of the controller is that we can force the user to drag an icon around a certain path in order to more safely switch modes within a controller. Dragging the selector around the corners of the polygon is much harder to do by accident than tapping a button or simply swiping left or right. This controller can have multiple modes with which the developer can restrict or allow certain types of transitions between states in the controller as needed.

Here's the basic setup with three possible selections:
![ScreenShot](http://i.imgur.com/7GjKJl3.png)


If we apply the polygon concept to a basic set of iPhone features that are usually tightly coupled, for example a set of iphone camera options that usually go together we can see the benefit of having a control that would be harder to accidentally alter:

![ScreenShot](http://i.imgur.com/7YmfCKL.png)

The features on this default iOS 8 camera could be coupled into one polygon controller if we wanted to make it easier to switch between all modes quickly.

![ScreenShot](http://i.imgur.com/MKm2nKL.jpg)
![ScreenShot](http://i.imgur.com/fWmGp8Q.png)

Lastly, one cool feature of this control could be using a single selector that animates an icon as it transitions between selected stages.
![ScreenShot](http://i.imgur.com/JuYKAqN.png)

Original Authors: Rodrigo Rallo & Matthew Davis, as R&D Studios.
