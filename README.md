### 기능 요구사항

- [x] controller를 @Controller를 활용하여 요청을 받도록 수정한다.
- [x] Jdbc Template을 이용하여 Connection을 직접 만들어주는 로직을 대체한다.
    - [x] boardDao에 적용한다.
    - [x] pieceDao에 적용한다.
- [x] Jdbc Template을 빈 주입을 받아서 사용한다.
    - [x] boardDao에 적용한다.
    - [x] pieceDao에 적용한다.

### 2단계 기능 요구사항

- [ ] 체스방 만들기
    - [x] localhost:8080 요청 시 노출되는 페이지에 `체스방을 만들 수 있는 버튼`이 있다.
    - [x] 방을 만드는 api를 구현한다.
    - [ ] 체스방 만들기 버튼을 누르고 `체스방 제목`과 `비밀번호`를 입력해야 한다.

- [x] 체스방 목록 조회하기
    - [x] localhost:8080 요청 시 체스방 목록을 조회할 수 있다
    - [x] 체스방 목록에는 `체스방 제목`과 `체스방을 삭제할 수 있는 버튼`이 표시된다.

- [ ] 체스방 목록에서 체스방 제목을 클릭하면 체스 게임을 이어서 진행할 수 있다.

- [ ] 체스방 삭제하기
    - [ ] 체스방 목록에서 체스방 삭제 버튼을 클릭하고 체스방 생성시 설정한 비밀번호를 입력하면 체스 게임을 삭제할 수 있다.
        - 진행중인 체스방은 삭제할 수 없다.
    - [ ] 체스방을 삭제하는 api를 구현한다.
