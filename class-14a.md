# Transforms
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

## Transform Syntax
 Includes the transform property followed by the value. The value specifies the **transform type followed by a specific amount** inside parentheses.

          div {
      -webkit-transform: scale(1.5);
         -moz-transform: scale(1.5);
           -o-transform: scale(1.5);
              transform: scale(1.5);
              }    
## *2D Transforms*
Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.

### 2D Rotate
Provides the ability to rotate an element from 0 to 360 degrees. 
* positive value will rotate an element clockwise.
* negative value will rotate the element counterclockwise. 
        

            .box-1 {
              transform: rota(20deg);
            }
            .box-2 {
              transform: rotate(-55deg);
            }


### 2D Scale
allows you to change the appeared size of an element,  therefore any value between
**.99 and .01**

               .box-1 {
                  transform: scale(.75);
                }
                .box-2 {
                  transform: scale(1.25);
                }
                
The **scaleX** value will scale the **width** of an element while the **scaleY** value will scale the **height** of an element.                
               
                   .box-1 {
                      transform: scaleX(.5);
                    }
                    .box-2 {
                      transform: scaleY(1.15);
                    }
                    .box-3 {
                      transform: scale(.5, 1.15);
                    }

### 2D Translate

works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.


              .box-1 {
                 transform: translateX(-10px);
               }
               .box-2 {
                 transform: translateY(25%);
               }
               .box-3 {
                 transform: translate(-10px, 25%);
               }
               
# Transitions & Animations
 transitions you have the potential to alter the appearance and behavior.animations can set multiple points of transition upon different keyframes.

                          .box {
                           background: #2db34a;
                           transition-property: background;
                           transition-duration: 1s;
                           transition-timing-function: linear;
                         }
                         .box:hover {
                           background: #ff7b29;
                         }
                         

..                         


                    
               
               