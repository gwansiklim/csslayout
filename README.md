# csslayout

css 심화 강의 모음 & 사용법

## flexbox

* flex를 사용할 때 조건은 첫번쨰로 부모에게 입력해야 실행이 가능하다. 만약 자식에게 사용할 경우 사용할 수가 없다.
* flex에서 가로로 움직이는 방식과 세로로 움직이는 방식이 있다. display:flex를 하면 기본적으로 row형태(가로형태)로 변환.
* justify-content는 자식들을 가로로 붙어 있게 할수도 있고 같은 간격으로 띄워 줄 수 있고, 가운데로 모아 줄 수 있다.
* align-items는 방향은 그대로 가로로인데 수평으로 움직이게 해준다. height를 이용해서 움직일 수 있다.
* flex-direction: column을 이용하면 중식축이 변환. 이때, 가로로되어 있던 중식축이 세로로 변경이 된다.
* class명:nth-child(2) 는 동일한 class명중에 2번째 자식을 가리키는 말이다.
* class명:nth-child()를 통해 순서를 바꿀수도 있고, 따로 지정한 자식만 변경이 필요한 경우에 사용을 한다.
* flex-wrap을 이용하면 width간격이 일정해진다.
* flex-shrink는 화면이 줄어들 떄 지정한 것을 다른것과 다르게 더 줄여주는(?) 역할이다.
* flex-grow는 shrink와 반대로 지정한 것을 크게 만들어 준다.
* align-self는 class명:nth-child()에 한개만 조작 할 수 있게 해준다. (flex-end, center)
* order는 순서를 변경?? 해준다고 이해를 했는데 이 부분은 좀 더 공부할 필요가 있을것 같다.

## Grid

* grid-template-columns: 250px 250px 250px; 이것은 3개의 box를 가로로 250px 만큼 늘려준다.
* grid-template-rows: 100px 50px 300px; 같은 경우에는 세로로 각 box마다 늘려준다.
* gap 같은 경우에는 각 box마다 전체적인 간격을 나눠준다.
* column-gap 같은 경우 가로로 얼마만큰 간격을 주는지 나타낸다.
* row-gap 같은 경우에는 세로로 얼마만큼 간격을 주는지 나타낸다.
* grid-template-areas는 각각의 box마다 색을 주고 변형을 줄 수 있게 해준다. 
<img src="file:///Users/gwansik/Desktop/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-10-28%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.28.23.png">

위의 사진처럼 각각 class에다가 사용할 명칭을 정해주고, 그리고 부모 class에다가 각각 하나씩 어떤 식으로 사용할지 넣어준다.

<img src="file:///Users/gwansik/Desktop/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-10-28%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.30.50.png">

만약 위와 같이 했을 경우 이런식으로 나타나게 된다.

*  grid-column-start: 1;, grid-column-end: 5; 을 사용을 할 줄 알면 위의 사진과 같이 똑같이 만들 수 있다.