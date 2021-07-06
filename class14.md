# class14 Reading:
### Transforms:
- Transform Syntax

                           -webkit-transform: scale(1.5);
                           -moz-transform: scale(1.5);
                           -o-transform: scale(1.5);
                           transform: scale(1.5);

#### 2D Transforms:   
Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
![2D Transforms](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)                        

- 2D Rotate
- 2D Scale
- 2D Translate
- 2D Skew

#### 3D Transforms:
![ 3D Transforms](https://www.found.co.uk/wp-content/uploads/2012/05/css3-3dtransforms-1.jpg)

- 3D Rotate
- 3D Scale
- 3D Translate
- 3D Skew
- Shorthand 3D Transforms

##### Transform Style:

To allow nested elements to transform in their own three-dimensional plane use the transform-style property with the preserve-3d value.


### Transitions & Animations:

*  Transitions:
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total:
-  transition-property
- transition-duration
- transition-timing-function
-  transition-delay

* Transitional Property
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.


- Transition Duration
The duration in which a transition takes place is set using the transition-duration property. 
- Transition Timing
The transition-timing-function property is used to set the speed in which a transition will move.
- Transition Delay
On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property

### Animations:

* Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

* Animation Name
- Once the keyframes for an animation have been declared they need to be assigned to an element.

* Animation Duration, Timing Function, & Delay
To start, animations need a duration declared using the animation-duration property. 

##### Customizing Animations:
Animations also provide the ability to further customize an element’s behavior, including the ability to declare the number of times an animation runs, as well as the direction in which an animation completes.
1. Animation Iteration
2. Animation Direction
3. Animation Play State
4. Animation Fill Mode


