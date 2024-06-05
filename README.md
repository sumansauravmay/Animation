# Animation

1. Transform

translateX- move to x axis
translateY- move to y axis
translate- move to x and y axis
ex-
transform: translate(-100px, 500px)

scale- to srink the element(2-two times the size, 3- three times of size)
scaleX- to shrink/stretch to x axis
scaleY- to shrink/stretch to y axis
ex-
transform: scale(3);

rotateX- rotate along x-axis
rotateY-rotate along y-axis
rotateZ- rotate along z-axis
rotate- rotate the element
ex-
transform: rotateY(180deg)

2. transition

transition show the effect in time
ex-
transition: 1s;
transition: background 1s;
it will apply only in background
transition: background 1s, transform 1s 1s ease-in;


keyframes

in the below example mario is the class name of image.
 .mario{
        height:150px;
        position: absolute;
        top: -40px;
        left:0px;
        animation-name: suman;
        animation-duration: 5s;

      }
      @keyframes suman {
        from{transform: translateX(0)}
        to{transform: translateX(1400px)}
      }

keyframes fill mode
it will not come back to initial phase
in the below example mario is the class name of image.
 .mario{
        height:150px;
        position: absolute;
        top: -40px;
        left:0px;
        animation-name: suman;
        animation-duration: 5s;
       animation-fill-mode: forwards;
      }
      @keyframes suman {
        from{transform: translateX(0)}
        to{transform: translateX(1400px)}
      }

Animation Delay
animation will start after 2 sec
 animation-delay: 2s;


ease-in means start slowly and then go fast
ease-out means start fastly and then go slow
ease-in-out means start and end go with slowly





