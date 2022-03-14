# jwp-dashboard-jdbc

### 미션 후기 / 리뷰

어우 저는 이번 미션이 제일 어려웠던 것 같아요. 해도 해도 마음에 안들고 찝찝한 느낌..?
학습 테스트 템플릿 패턴, 콜백 패턴이 낯설어 뭔가 이해는 됐는데 이걸 어떻게 써먹어야하지 고민에 리팩토링이 늦어졌어요.

템플릿 패턴을 잘 쓴건지. 구구가 의도하신바가 맞는지가 궁금하고,
콜백 인터페이스명이 QueryCallBack인데 이게 일반적인 네이밍인가 확신이 안서네요. 더 좋은 이름이 있을까요?
app 모듈은 이번에 제작한 jdbc 모듈을 사용하는 사용자의 몫이라고 생각하여 테스트 코드에 힘쓰지 않았어요.
반대로 jdbc 모듈에서 어떻게 하면 DB나 실제 쿼리에 의존적이지 않으면서 프레임워크를 확인, 설명할 수 있는 테스트 코드를 짤 수 있을까를 고민했습니다. [요놈 :)](https://github.com/ecsimsw/jwp-dashboard-jdbc/blob/step1/jdbc/src/test/java/nextstep/jdbc/executor/PreparedStatementExecutorTest.java)
