Query-> a question, especially one expressing doubt or requesting information.

default context:
in a perfect or suitable screen size
use default styles
````
body{
    background-color: lightblue;
    transition: 10s ease-in-out backgroun-color;
}


````
but when you want to add context to a specific screen size
````
  css

````
@media(min-width:400px){
    body{
    background-color: lightgreen;
    }
    .conatiner{
        width:80%;

    }




    --->positioning

    /*basically position static and relative are the same
in the old days some browsers used static and others supported relative 
*/
/* wenn you say absolute then you have to say where it must be given top,left,z-index and absolute
wenn you give absolute it losses during scrolling down but fixed it doesnot get lost by scrolling   */
/* absolute and relative require position to be set positions are 
1. left     3. top
2. right    4. bottom  
absolute positioned element hides on scroll while fixed positioned element stays on the screen

sticky is a combination of relative and fixed 
it is relative until it reaches a certain point then it becomes fixed
in sticky position specifying the position is not important because it can by
default take relative position
but then it remains relative until it reaches a certain point then it becomes fixed

*/

/* the following are the positioning styles
  1. static        3. absolute             5. sticky
  2. relative      4. fixed 
*/




