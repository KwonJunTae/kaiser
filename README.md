 Kaiser 팀 프로젝트
조원 : B189005 권준태, B189007 김봉섭

○ 설계
   - 설계키워드 : NFC, 기숙사, 인증, 점호
   
   - 설계내용 : 현재 기숙사 점호는 사람이 각방을 방문하면서 인원을 체크한다. 그러나 각 방에 NFC리더기를 설치하여 층장 없이 사생이 직접 스마트폰 NFC를 이용하여 개인인증을 통해 점호를 할 수 있게 한다.
   
   - 설계계획
   
     ① 자료수집 : 점호시스템 분석

     ② 기능정의 : 사용자 정보 저장 및 비교, 관리자 모드 설정
     
     ③ 소스코딩 : 사용자 클래스, 관리자 클래스, 정보확인 클래스 등
     
     ④ 단위테스트 : 각 클래스의 연관관계가 정상적으로 이루어 지는지 확인
     
     ⑤ 통합테스트 : 최종적으로 프로그램이 실행되는지 확인
     
     ⑥ 결과보고 : 결과보고

○ 요구사항
   - 학생은 개인정보(아이디,비밀번호,이름,성별,나이 등)를 입력하여 시스템에 가입한다.
   - 시스템 가입시 중복된 아이디가 없는지를 확인하고, 없다면 가입이 이루어진다.
   - 남자관리자는 남학생의 점호여부를 확인할 수 있다.
   - 여자관리자는 여학생의 점호여부를 확인할 수 있다.
   - 관리자는 시스템에 등록된 학생의 호실, 층 별로 점호를 조회할 수 있다. 이로인해 점호 시 각 방에 누가 있고 없는지를 조회할 수 있다. 
   - 각 학생은 점호 시 방에 설치된 NFC리더기에 자신의 고유 NFC 정보를 지니고 있는 스마트폰을 접촉함으로써 점호를 인증한다.
   - 각 학생이 점호를 인증할 시 시스템은 등록되어있는 NFC인지를 확인하고 그 NFC에 해당하는 학생의 호실과 시스템의 호실이 같은지를 확인한다. 같다면 점호인증이 된다.
   - NFC를 사용할 수 없는 학생(ex.아이폰)들은 다른 교통카드나 체크카드, 신용카드를 본인의 NFC정보로 등록하여 인증을 대체한다.
   - 관리자는 각 학생의 호실 및 이름, ID을 입력한 후, 택배,우편 유무를 등록할 수 있다. 만약 틀리다면 입력을 하지 못한다.
   - 학생은 택배,우편 유무를 확인할 수 있다.
   - 관리자는 공지사항을 등록할 수 있다.
   - 학생은 공지사항을 확인할 수 있다.
