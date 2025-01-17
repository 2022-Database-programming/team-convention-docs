## Commit message Convention
### Message Type List
![image](https://user-images.githubusercontent.com/96467030/198984702-a7dfecfa-f123-4cde-aaeb-97a74f0ecfec.png)
- 코드를 수정한 경우 Modify Type 사용
- Github issue 번호에 따라 다음과 같은 규칙으로 작성한다.
- issue number 26 → [Type]: #[issue number] [commit message] [message body]
- Type은 현재 시제로 작성하도록 하며, 대문자로 작성하지 않는다.
- Message는 무엇을 했으며 왜 했는지 적어준다.
![image](https://user-images.githubusercontent.com/96467030/200120111-6b186c72-c2af-4769-a669-efc1335b4938.png)
- **기능 구현 단위로 commit** 하도록 하고, 기능 구현이 완료되면 반드시 PR 및 코드 리뷰를 받도록 한다
- [AngluarJS commit convention (번역본)](https://velog.io/@outstandingboy/Git-커밋-메시지-규약-정리-the-AngularJS-commit-conventions#커밋-메시지-헤더-commit-message-header)

## Code Convention
### Backend
- [캠퍼스 핵데이 Java 코딩 컨벤션](https://naver.github.io/hackday-conventions-java/)
- [좋은 코드를 위한 자바 변수명 네이밍](https://tecoble.techcourse.co.kr/post/2020-04-24-variable_naming/)
- [좋은 코드를 위한 자바 메소드 네이밍](https://tecoble.techcourse.co.kr/post/2020-04-26-Method-Naming/)
### DB
- [MySQL 네이밍 규칙](https://killu.tistory.com/52)

## Github Issue Convention
- 각 스프린트에 맞게 이슈를 발급한다 (**이슈 템플릿 사용하기!**)
- 완료, 진행중, 오류 3개의 라벨을 달아 현재 스프린트의 상태를 표시한다.
- 완료된 이슈는 PR 확인 후 Close 한다.
![image](https://user-images.githubusercontent.com/96467030/198984745-f80becbd-07f4-483c-b810-bb9b41c7364c.png)
## Github Branch Convention

- branch 생성 시에도 커밋 메시지와 같은 방식으로 작성한다.
- feature/#issueNumber-branchName
- 브랜치 이름에는 띄어쓰기 대신 -를 사용한다.

## PR 및 Branch 생성 시 주의 사항

```
1. 머지 시 메인 브랜치와 충돌 날 우려가 있기 때문에 PR전 반드시 체크해주세요!
2. PR을 보낼 때는 수정 사항 및 구현 사항, 이에 대한 결과를 이미지와 함께 올려주세요.
3. 코드 리뷰 확인 후 머지 승인 시 머지 후 이슈를 닫아주세요.
4. 이슈번호와 브랜치번호를 일치시켜주세요.
5. 커밋 컨벤션을 지키고, 브랜치 번호를 일치시켜주세요. 브랜치 번호에 따라 이슈에
   커밋 메시지가 기록됩니다. 잘못된 번호가 기록되지 않게 주의하세요.
6. 만약 문제가 있다는 코멘트를 받으면, PR을 닫고 수정 후 다시 PR 날려주세요.
```
<img width="913" alt="스크린샷 2022-11-05 오후 11 30 40" src="https://user-images.githubusercontent.com/96467030/200124862-2f7f7393-1dde-4a33-907e-8a8b76d7cc15.png">
