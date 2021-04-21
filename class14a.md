# Welcome to reading notes code 201 class 14-a:

- What I have understood from the article, of Julia Rozovsky journey to find her true passion and how she landed her dream job at google to study people’s habits and tendencies and how *Project Aristotle* the one she was assigned to help her in achieving her goal,  is the following:
- **Psychological safety** and **emotional conversations** are integral parts of the success of team working. 
- What also influence the psychological safety are what called **group norms**.
- **Norms** are the traditions, behavioral standards and unwritten rules that govern how we function when we gather.

![teamwork picture](https://www.i2idirectmarketing.com/wp-content/uploads/2020/06/teamwork-quotes.png)

- One important aspect we might couldn’t realize that a good experience is an important base for success and I quote from the article :
 >it’s sometimes easy to forget that success is often built on experiences  like emotional interactions and complicated conversations and discussions of who we want to be and how our teammates make us feel

## Now we will talk about interesting topic , animation and 2D and 3D styling :

![animation using css](https://stfalcon.com/uploads/images/5881e0b98e717.png)

- With the introducing of CSS3 many cool layout properties has been available and how to position and change elements look.
- One of those properties is **transform** property m which comes in two settings 2D and 3D.


### So, what is the syntax to use it ?
- Pretty simple you just add the transform property followed by the value which determines what the type is, followed by a specific amount inside parentheses.
### How to transform elements on 2D plane?
- By using the 2D values, one of them is **rotate** which provides the ability to rotate an element from 0 to 360 degrees.
- Another 2D value is the **scale** value which control the appeared size of an element.

- Also, we have **The translate** value works like pushing and pulling an element in different directions.

- Also, we can combine those values and in order to combine transforms, list the transform values within the transform property one after the other without the use of commas.

### How about 3D plane?

- In 3D plane we will be able to alter elements on the **horizontal** and **vertical** axes and the **z axis**, giving us control of depth.

- In order for three-dimensional transforms to work the elements need a **perspective** from which to transform.
- You can use the perspective value *within* the transform property, or applying it to the parent element.
- Its value could either set as *none* or a *length measurement*.

- So, the properties for 3D will be the same as 2D but by adding a third value for the z axis.

- Meaning we will have the following properties:
1-3D rotate.
2-3D translate.
3-3D scale.

- By using 3D transforms this might cause them to face away from the screen,so if you prefer not to see these elements at all, set the **backface-visibility** property to **hidden**.

### Now let’s talk about Transitions:

>With **CSS3 transitions** you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

- The **transition-property** property determines what properties will be altered in addition with the other transitional propertv.

- You need to pay attention that, not all properties may be transitioned, only properties that have an identifiable halfway point.

- The **transition-duration** property set the duration in which a transition takes place.

- We also have **transition-timing-function** property which is used to set the speed in which a transition will move and one of its values is **linear** identifies a transition moving in a constant speed.

### Another important and interesting topic , Animation:

### For what we use it?
- To set multiple points at which an element should undergo a transition.
- For animation we use what we call **@key-frames** rules.

- It consist of the following:
1- Animation Name; is applied to the element in which the animation is to be applied to.
2-Animation Duration.
3- Animation Timing Function.
4- Animation Delay.

**Other properties**;

- **animation-iteration-count property**;
- We use it to have an animation repeat itself numerous times as by default, animations run once and then stop. 

- **Animation Fill Mode**
- The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run. The animation-fill-mode property accepts four keyword values, including none, forwards, backwards, and both.

- The **animation-play-state**:
 - This property allows an animation to be played or paused.
