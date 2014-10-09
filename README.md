<p align="center">
  <img src ="https://raw.githubusercontent.com/remirobert/Anim/master/ressources/logo.gif"/>
  <h1 align="center">Anim</h1>
</p>


Anim allows you to use animations very easily. You can use it in your UIKit application for make smooth animations, using Swift. 


<h1 align="center">Features</h1>

 - Position (CGPoint)
 - Bounce effect
 - Resize (CGSize)
 - Rotation
 - Rotation X
 - Rotation Y
 - Rotation Z
 - Fade
 - Border raduis
 - Move circle
 - Animations sequence
 - Repeat animations
 
<h1 align="center">How to use it</h1>

You can use Anim with all Layers (UIButton, UItableViewCell, UItextField, UIView, ...).
Anim provides a extension for CALayer, for use animation: 

```Swift
let animation = Animation.movePosition(CGPointmake(30, 30), delay: 1.5)
self.myView.layer.runAnimation(animation)
```
