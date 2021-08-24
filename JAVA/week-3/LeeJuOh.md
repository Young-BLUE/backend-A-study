### 정리글
---
|주차|제목|링크|
|---|---|---|
|3주차|스트림으로 데이터 수집|[링크](https://velog.io/@ljo_0920/%EB%AA%A8%EB%8D%98-%EC%9D%B8-%EC%9E%90%EB%B0%94-%EC%95%A1%EC%85%98-%EC%8A%A4%ED%8A%B8%EB%A6%BC%EC%9C%BC%EB%A1%9C-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%88%98%EC%A7%91)|
| |병렬 데이터 처리와 성능|[링크](https://velog.io/@ljo_0920/%EB%AA%A8%EB%8D%98-%EC%9D%B8-%EC%9E%90%EB%B0%94-%EC%95%A1%EC%85%98-%EB%B3%91%EB%A0%AC-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%B2%98%EB%A6%AC%EC%99%80-%EC%84%B1%EB%8A%A5)|

</br>

### 궁금증 및 회고록
---
스트림의 collect()는 리듀싱 연산을 이용해서 스트림의 각 요소를 방문하면서 컬렉터가 작업을 처리한다는 개념을 이해하려 했고
Collections 클래스의 유용한 Collector들을 반환하는 정적 팩터리 메서드이 무엇이 있는지 위주로 학습을 진행했다.


</br>
스트림의 병렬처리 챕터를 학습 후 든 생각은 병렬 처리가 만능이 아니라는 점이 더 강하게 느껴졌다. 또 JMH라이브러리의 존재를 알 수 있게 되어서 좋았다. 특히 병렬 스트림은 사용하기에는 너무 편하지만 오히려 성능이 악화될 수 있으니 사용할 일이 생긴다면 성능 측정 단계를 반드시 도입할 때 확인하여 보수적으로 사용해야 겠다고 생각했다.