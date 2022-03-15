# Animation   

- @keyframe을 이용하여 css animation 효과를 지정한다.     

- 0% ~ 100% 까지의 animation을 조절할 수 있다.   
(sprite 이미지를 **background-position**을 이용해서 나타낼 수 있다.)

    ```
    @keyframes spaceship-ani {
        to {
            background-position: -2550px 0;
        }
    }

    // 이미지 기존 위치의 0,0을 -2550px 0 로 끌어당기는 효과
    ```   

    *0%와 100%는 따로 표시없이, from - to 로 대체 가능하다.*     


- ### gif와의 차이   

    - 만들어져 있는 gif파일을 쓰면 편하겠지만, 
    css는 코드로 조절할 수 있는 장점을 가지고있다.

    

