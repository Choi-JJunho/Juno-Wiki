# 레벨1 자동차경주 회고

페어 박스터와 함께 첫 미션 자동차경주를 진행했다.

우연히 같은 온보딩 조가 되었고, 우연히 같은 페어가 되었는데, 거기에 같은 신림에 사는것도 모자라 집도 가까운 페어를 만나서 너무 신기했다.
신림에서 같이 등,하교도 하면서 미션에 대한 이야기도 같이해서 미션 내내 페어프로그래밍한 기분이였다 ㅋㅋㅋ

사실 이전에 우테코 최종 코테준비를 위해 대전 스터디원들과 한번 자동차경주 미션을 진행했봤는데 1월동안 놀면서 다 까먹었다... Java, IntelliJ, 테스트작성, 자동차경주 규칙... 어떻게하더라;;
굳어버린 머리와 생소한 규칙에 멘붕 😵‍💫

원래는 1, 2단계로 나눠서 회고를 하려고했으나... 기간이 짧아 작성할 내용도 많이 없어 묶어서 쓰려고한다.

# 소프트스킬

페어프로그래밍을 진행하면서 하나의 컴퓨터에 두명이 붙어있는 모습이 처음에는 정말 어색했다.
미션 전체적인 진행과정에서 소프트 스킬에 대해 다양한 경험을 할 수 있었다.

> 💡 소프트스킬?
소프트 스킬이란 다른 사람과 함께 일하고 상호작용하는 방식을 나타내는 대인관계 스킬을 의미한다.

## 좋았던 점

- 대화를 나누는 과정에 있어서 자신의 의견을 주장하는 연습을 많이 할 수 있었다.

내가 페어를 설득하고, 페어가 나를 설득하는 과정에서 서로의 주관을 확인할 수 있었던 부분이 좋았다.

- 리뷰어의 질문에 대해 `틀렸나?`라는 생각보다 `나는 이렇게 생각해서 이러한 코드를 작성했다!`라고 의견을 어필하는 과정이 너무 좋았다.

여기에서는 `정답은 없다`라는 생각을 계속해서 리마인드 시켜줄 수 있었다.

## 아쉬웠던 점

- 모든것이 처음이고 생소해서 처음부터 잘해야겠다 라는 생각을 조금이나마 갖고 있었던 것이 아쉬웠다.

4시간동안 객체간 의존도, 설계 등을 열심히 해봤지만 막상 코드를 작성하니 엉망이 되어버렸던 상황이 있었다.
실무 개발을 하러 온 것도 아니고 배우려고 왔는데 잘해야한다는 강박이 있었던게 조금은 아쉬운 부분이다.

- 연극, 생활규칙, 미션 등등 초기에 많은 정보가 몰아쳐서 정작 미션에는 많은 시간을 들이지 못한 것 같아 아쉬웠다.

- 아무래도 첫 미션이기도 하고 제한시간 내에 내야한다는 조급함 때문에 성급하게 미션을 수행한 것 같아 아쉬웠다.

페어와 보다 많은 토론을 하고 자신의 견해를 주장하는 시간이 조금 더 많았으면 좋았을 것 같다는 아쉬움이 있었다.

# 하드스킬

하드스킬에 대한 부분도 빼먹을 수 없다 🔥

> 💡 하드스킬?
하드 스킬은 특정 훈련을 통해 개발할 수 있는 스킬을 의미한다.

## 좋았던 점

- 리뷰어에게 다양한 의견을 물어보고 이에 대한 생각을 들어볼 수 있어서 좋았다.

해당 과정에서 다양한 키워드를 제시받을 수 있어서 좋았다.
특히 개인적으로 궁금했던 메소드 파라미터의 final에 대한 부분에 대한 의견을 들어볼 수 있어서 좋았다.
해당 부분은 개인적으로 글로 정리했다.
[함수 파라미터의 final 키워드](https://velog.io/@junho5336/%ED%95%A8%EC%88%98-Parameter%EC%9D%98-final-%ED%82%A4%EC%9B%8C%EB%93%9C)

- 전략패턴에 대해 알게 되었다.

랜덤한 값을 출력하는 클래스에 대한 테스트를 진행하기 위해 전략패턴을 사용하여 인터페이스로 분리하는 과정이 있었다.
이를 통해 결과를 유추할 수 없는 어떠한 기능에 대해서는 인터페이스로 분리하여 해당 행위를 임의로 Mocking하여 테스트를 진행할 수 있다는 점을 배웠다.

- unmodifiableList의 반환에 대한 생각을 해볼 수 있었다.

"반환받은 외부에서 수정하지 않게, 데이터가 수정될 수 없어야하기 때문에 unmodifiableList를 사용해야한다" 정도로만 생각하고 사용하고있던 부분에서 리뷰어에게 막상 질문을 받으니 명확한 근거를 제시하기가 어려웠다.
이에 대한 참고자료를 제공받을 수 있어 막히던 부분을 빠르게 해소할 수 있었다. 

[가변객체 vs 불변객체](https://steady-coding.tistory.com/559) 
[방어적 복사와 Unmodifiable Collection](https://tecoble.techcourse.co.kr/post/2021-04-26-defensive-copy-vs-unmodifiable/)

unmodifiableList를 반환함에 있어 해당하는 메소드의 네이밍이 getSomthing() 정도로 그친다면 unmodifiableList를 반환할 것을 예측하지 못해 별도의 예외처리를 해줘야하는 상황에 맞이할 수 있다는 견해도 들을 수 있었다.

- toString의 용도에 대해서 생각해 볼 수 있었다.

Car 객체의 toString를 재정의 하는 과정에서 필드 값을 임의의 출력형태로 변환하여 반환했었다.
이 부분에 있어 도메인이 View를 의존하게 되어 MVC 패턴을 위반하는 상황이 오기도 하며 다른 개발자에게 혼란을 야기할 수도 있다는 의견을 들을 수 있었다.

때문에 toString은 로깅용도 이외에는 사용을 지양해야하며, View로 변환하기 위한 별도의 로직을 외부에서 구현하는 것이 바람직하다고 생각한다.

관련하여 동일한 고민을 한 다른분의 게시물도 참고할 수 있었다. (역시 사람생각은 똑같나보네요 😂)
[Java 에서 toString 메소드의 올바른 사용 용도에 대하여](https://hudi.blog/java-correct-purpose-of-tostring/)
> ex) `position = 3;` -> 출력형태 : "---"


## 아쉬웠던 점

- git commit message를 영어로 작성하면서 커밋 메시지를 작성하는 데 시간이 더 오래걸리는 불상사가 있었다.

다음에는 보다 익숙한 한글로 커밋 메시지를 작성하는 방향으로 진행해봐야겠다는 생각...

- 테스트명도 영어로 작성해서 @DisplayName으로 두번 작업하는 느낌이 들어 아쉬웠다.

테스트에 대해 `메소드 명을 한글로 해도 괜찮은가?` 에 대한 생각은 상황에 따라 좋고 나쁨이 갈리지만, 미션을 진행하는 동안에는 한글 메소드명을 작성해도 무관할 것 같다는 생각이다.
그래도 왜? 라는 질문에 대답할 수 있을정도의 근거는 항상 생각해두는 것이 좋겠다.

- 미션을 제출하는 과정에 있어서 익숙하지 못해 시간을 많이 빼앗겼던 부분이 아쉬웠다.

중간에 프리코스 미션처럼 수행하면 되겠지.. 라는 생각으로 메뉴얼을 소홀하게 읽었던 부분이 과제를 제출하는 과정에서 문제를 야기했었다.
내가 당연하게 알고있다고 생각해도 한번쯤은 의심하고 주어진 메뉴얼을 꼼꼼하게 읽어볼 필요가 있다는 교훈을 얻었다.

# 페어프로그래밍

페어에게 좋았던 점과 아쉬웠던 점을 정리해보려고한다.

## 좋았던 점

- 나의 의견을 듣고 그 근거를 물어보는 과정이 좋았다.

- 흡연자임에도 불구하고 미션을 진행하는 과정에서는 단 한번도 중간에 흡연하러 가는 모습이 없었다.
절제력이 대단한건지 몰입력이 대단한건지 뭐가 되었든 엄청 대단하다 👍

- 페어에게 전략패턴을 배울 수 있었다.
자기는 아니라고하지만 나보다 훨씬 잘한다 👍 반박시 내말맞

## 아쉬웠던 점

- 중간중간에 둘다 예스맨이 된 것 같은 부분에서 아쉬움이 컸다.

서로의 의견을 너무 존중해주다 보니 생각의 차이로부터 나오는 토론이 자주 없었던 것이 아쉽다. 😭
아니면 박스터랑 너무 잘맞아서 그런걸지도..?! 그러면 좋은점인데 🥺

- 의견을 수용하는 과정에서 일부 근거를 물어보지 않아 아쉬운 부분이 있었다.

어떤 방법을 제시했을 때 페어가 시도해보지 않은 방법이기 때문에 사용해보고 싶다. 라고 넘어갔던 부분에 대해서 뭔가 더 열띈 토론을 이어나갈 수 있지 않을까 라는 아쉬움도 있었다.

> 박스터 보고있나..🥸

# 정리

첫 페어프로그래밍인데다가 온보딩 과정까지 곂쳐서 과정을 이해하는 데 더 많은 시간과 정신을 쏟았던 미션이다.
소프트, 하드스킬의 증진보다는 미션 진행과정에 익숙해지는 것에 더 중점을 둔 미션이였지만 그럼에도 배울점은 많았다.
앞으로 만날 페어 혹은 팀원들에게 부끄럽지 않은 사람이 될 수 있도록 노력해보자 🔥

[🏎️ 자동차 경주 - 1단계 PR](https://github.com/woowacourse/java-racingcar/pull/442)

[🏎️ 자동차 경주 - 2단계 PR](https://github.com/woowacourse/java-racingcar/pull/565)