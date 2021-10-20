# csslayout

css 심화 강의 모음 & 사용법

## flex

* flex를 사용할 때 조건은 첫번쨰로 부모에게 입력해야 실행이 가능하다. 만약 자식에게 사용할 경우 사용할 수가 없다.
* flex에서 가로로 움직이는 방식과 세로로 움직이는 방식이 있다. display:flex를 하면 기본적으로 row형태(가로형태)로 변환.
* justify-content는 자식들을 가로로 붙어 있게 할수도 있고 같은 간격으로 띄워 줄 수 있고, 가운데로 모아 줄 수 있다.
* align-items는 방향은 그대로 가로로인데 수평으로 움직이게 해준다. height를 이용해서 움직일 수 있다.
* flex-direction: column을 이용하면 중식축이 변환. 이때, 가로로되어 있던 중식축이 세로로 변경이 된다.
* class명:nth-child(2) 는 동일한 class명중에 2번째 자식을 가리키는 말이다.
* class명:nth-child()를 통해 순서를 바꿀수도 있고, 따로 지정한 자식만 변경이 필요한 경우에 사용을 한다.
* flex-wrap을 이용하면 width간격이 일정해진다.
* 