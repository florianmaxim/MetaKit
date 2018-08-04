#  Meta for iOS

## "Super-high level" XR (VR/AR) API for iOS.

Introducing meta objects.

```swift
import SceneKit
import MetaKit

class GameViewController: UIViewController {

    override func viewDidLoad() {
    super.viewDidLoad()

    var m = Meta(_view: self.view as! SCNView)

    var c = Cube(width: 1, height: 1, length: 1)

    }
}
```

## Basic concepts

Meta objects are basically objects extended by methods that objects in the real world do not have. 

The chair you are sitting on for example doenst really seem to have an .invisible() function (at least none that us humans know about). In virtual media like AR/VR it is possible to hide the visual representation of a chair without removing it's rigid body from the physical world.

A meta object can but doesn't necessarily need to have a graphical representation or a physical body.



