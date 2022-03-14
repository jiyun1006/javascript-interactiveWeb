# CSS Transform   

- ## transform의 장점   
    - **기준점** 자체를 바꿀 수 있다.(**transform-origin**)      
    (*width나 height는 정해져있음.*)   

    - **하드웨어 가속**을 통해 성능을 향상시킬 수 있다.(gpu 사용가능)      
    (*position을 이용해 위치를 바꾸는 것 보다 성능이 좋다.*)   

    - **cubic bezier**을 이용해서 transition의 변환 곡선을 조절할 수 있다.    

        <img src="https://user-images.githubusercontent.com/52434993/158142558-2aad301d-50b3-4b3a-8b97-befa84f9e4f3.png">

        (*포인터를 조절해서 속도를 조절 가능하다.*)   

    - 