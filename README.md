# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)


## Step2 요구사항 기능 분해해보기
* [X] 빈 문자열 또는 null 값 입력한 경우 0 반환
* [X] 숫자 하나를 문자열로 입력할 경우 해당 숫자를 반환
* [X] 숫자 두개를 컴마(,) 구분자로 입력할 경우 두 숫자의 합을 반환
* [X] 구분자를 콜론(:)을 사용할 수 있다.
* [X] "//"와 "\n" 사이에 커스텀 구분자로 지정할수 있다.
* [X] 숫자 이외의 값 또는 음수를 전달하는 경우 RuntimeException 예외가 발생해야한다.


## step3 요구사항 기능 분해
* [X] 움직일 자동차 댓수를 입력 받는다.
* [X] 자동차들이 이동할 횟수를 입력받는다.
* [X] Random 값을 사용하고 0-9 범위의 숫자를 활용한다.
* [X] 자동차 별로 Random값을 가져온다.
* [X] 자동차 별로 Random값 4-9이상인 경우 전진한다.
* [X] 자동차 별로 Random값 0-3인 경우 멈춘다.
* [X] 자동차 상태를 출력할 수 있다.(출력 시점 제약 X)

### 프로그래밍 요구사항
1. 모든 로직에 단위 테스트 구현 필요
2. 자바 코드 컨벤션 지키기(⌨️ 단축키 : opt + cmd + L) [🔗 참고링크](https://www.jetbrains.com/help/idea/code-style-java.html)
3. else 예약어 사용하지 않기 (switch 포함)
4. git commit convention 지키기 [🔗 참고링크](https://gist.github.com/stephenparish/9941e89d80e2bc58a153)


## step4 요구사항 기능 분해
* [ ] 각 자동차에 5자 이내로 이름을 설정할 수 있다.
* [ ] 진행 결과 출력할 때 자동차 이름을 같이 출력한다.
* [ ] 자동차 이름은 쉼표로 구분한다.
* [ ] 자동차 경주 완료 후 우승자를 알려준다.
* [ ] 우승자는 한명 이상일 수 있다.