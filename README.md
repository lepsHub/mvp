# mvp
Learn about MVP design pattern

Model:
- Simple as a model which the app is going to show.
- Doesn't have a reference to anything else.

View/ViewController:
- Responsable for user interface
- Maybe you get confuse using ViewController but in this pattern ViewControllers be the view as part of MVP.
- We need a **reference** in the view to the *presenter*.

**NOTE:**
There is a UIAlertController view that is commented because the example makes you think if it's better to manage this component in the View or presenter.

Presenter:
- **The glue that ties everything together**
- Has a **reference** to:
  - View
 - Needs to present the view and tell the view what to do.
