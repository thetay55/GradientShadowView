# GradientShadowView
Customize your gradient, shadow view inside the storyboard, xib

# Use
- Just drag this class into your project
- In your storyboard, select a UIView
- Go the the identity inspector and in the class field, type GradientShadowView instead of UIView
- Play with the attributes inspector with real-times results!
  you can select two colors for the gradient and one color for the shadow
  you can choose the shadow position (x/y) and its blur
  the direction of the gradient (top left is 0,0 and bottom right is 1,1) from the start point to the end point
  the corner radius of your view
  you can animate the gradient to another one by calling the animate(duration: TimeInterval, newTopColor: UIColor, newBottomColor: UIColor)method
  
  
  ![](https://github.com/thetay55/GradientShadowView/blob/master/Screen%20Shot%202019-03-13%20at%202.59.35%20PM.png)
