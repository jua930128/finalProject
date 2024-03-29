# finalProject
파이널프로젝트(ORDER BY)
<br><br>
🔥 수행기간<br>
2023년 03월 06일 ~ 2023년 04월 27일
<br><br>
🔥 개발 목표<br>
비용 문제로 평소에 쉽게 접할 수 없는 특별한 차량과 오토바이를 경험해보고 싶은 성향의 사용자들을 위해 사이트를 기획하였습니다.
기존 자동차와 오토바이를 한 사이트에서 한 번에 검색하고 대여할 수 없는 단점을 보완하기위해 차량과 오토바이 카테고리를 세분화하여 사용자가 쉽고 편리하게 사용할 수 있도록 목표를 정했습니다.
<br><br>
🔥 개발 환경<br>
운영체제	Window OS, Mac OS <br>
개발도구	Eclipse, Spring Tool Suite3, Visual Studio Code <br>
DBMS	Oracle Database 11g Express <br>
Server	Apache Tomcat 9.0 <br>
Language	Java 11, JavaScript, Ajax, JSP, HTML5, CSS3 <br>
디자인툴	HTML5, CSS3, Jquery, Bootstrap
<br><br>
🔥 프로젝트 시 활용해본 대표 기술<br>
DB설계 및 Mybatis 활용 <br>
프론트 JSP작업 시 JQuery와 Bootstrap에 있는 오픈 css를 메인 플로팅 배너에 적용 <br>
Ajax를 이용하여 데이터베이스와 비동기식으로 아이디 중복체크 적용 <br>
Spring mailx library를 사용하여 회원가입 시 이메일 인증 구현 <br>
Spring Security를 활용한 인증, 권한 및 예외처리 적용 <br>
Spring Security remember-me를 사용하여 로그인 상태 유지 <br>
Spring Security Web을 사용하여 IP 접근을 제어함으로써 보안을 강화 <br>
naver, kakao Open API를 사용한 간편 로그인 <br>
주소API를 사용하여 간단하게 주소검색 및 입력 가능 <br>
MVC패턴을 이용한 REST API 설계 <br>
GitHub를 이용하여 형상관리 <br>
Jira를 사용한 협업과정 기록
<br><br>
🔥 구현 기능<br>
관리자 페이지 : 차량, 오토바이, 지점을 수정 및 등록 가능 / 회원 관리 / 총 차종수, 매장 수, 결제금액 확인 / 쿠폰 관리 / 실시간 상담 관리 / 결제 내역 확인 <br>
메인 페이지 : 차량2대, 오토바이 1대를 30% 저렴하게 대여하는 차종 3개와 결제 수가 가장 많은 차량,오토바이 각각6대 씩을 보여주며 바로 결제 가능 / 팝업창을 통하여 실시간으로 카톡 채팅, 메인 페이지 우측에 떠 있는 플로팅 배너로 비회원이 관리자에게 문의를 보낼 수 있습니다. 특가 / 인기 차종을 바로 예약페이지로 넘기는 기능이 있습니다. <br>
로그인 : Spring Security-OAuth2 소셜 로그인과 일반 회원 로그인을 할 수 있습니다. <br>
회원가입 : 회원가입 시 이메일 인증을 거쳐야 하며 필수항목(아이디, 비밀번호, 비밀번호 확인, 이름, 생년월일, 이메일, 인증번호 확인)을 입력해야 가입할 수 있습니다. <br>
예약 페이지 : 예약 시, 사용자가 선택한 정보 출력 및 사용자가 선택한 날짜가 출력됩니다. <br>
결제 페이지 : 회원의 등급에 따른 등급 출력, 회원의 쿠폰 목록, 쿠폰 별 할인 금액 총금액에 적용 + 회원이 보유한 포인트 출력 및 적용되며 사용자가 선택한 상품 및 일자에 따른 정보를 넘기고 결제 버튼으로 결제 API에 연동됩니다. <br>
결제 성공페이지 : 결제 완료 후 예약 정보 데이터베이스에 저장됩니다. <br>
공지사항 : 글 작성 및 취소 시큐리티를 통해 관리자만 글쓰기 수정 삭제 등이 가능하도록 구현하였습니다. <br>
회사소개페이지 : 회사의 최근 연혁이 상위로 올라가게 보입니다. <br>
마이페이지 : 회원 정보 불러온 후 수정, 결제내역, 찜 내역, 예약내역 정보 불러오기를 할 수 있습니다. <br>
예약페이지 : 달력은 2달씩 보이도록 되어있고 현재 날짜의 기준으로 이전 날짜는 선택 불가능하며, 대여 날짜와 반납날짜 선택 후 지도 출력 후 지도 선택 후에 지점에서 보유한 차종을 선택할 수 있습니다. 원하는 브랜드를 고를 시 해당 브랜드만 보여줍니다. 이미지 클릭 시 해당 차의 상세 정보를 보여주며 x 버튼, 모달 바깥부분, ESC 키를 누를 시 모달이 사라지며 선택버튼을 누를 시 차가 선택되며 결제창으로 정보를 넘깁니다.
<br><br>
🔥 담당 역할/기여도<br>
[담당 역할]<br>
프로젝트 주제 선정, 기획 및 DB설계, 홈페이지 컨셉과 전반적인 레이아웃 설정, 메인 페이지, 메인 플로팅 배너(빠른 문의, 카카오톡 오픈채팅 바로가기), 로그인 페이지, 회원가입 페이지, 회사소개 페이지, PPT준비 및 발표 <br>
[기여도]<br>
25% (총 구성원 5명)
<br><br>
🔥 프로젝트 참여소감<br>
세미프로젝트 당시 시간분배의 중요함을 인지하고 있었던 덕에 파이널 프로젝트는 최대한 시간을 쏟는 것에 집중했습니다. 그리하여 제가 맡은 분량은 잘 해낼 수 있었으나, 어려움을 겪고 있던 조원을 돕지 못했고 그로 인해 시연 과정에서 연결이 매끄럽지 못해 아쉬움이 많이 남습니다. 그리고 함께하는 프로젝트인 만큼 조원과의 소통에도 중점을 두었고 화기애애한 분위기에서 프로젝트가 마무리되어 기분이 좋습니다. 두 번의 소중한 경험으로 자신감이 상승하였고 개인적으로 다음 프로젝트는 Spring Boot을 활용하여 혼자 진행하고 전체적인 부분을 모두 경험해보고 싶습니다.
<br><br>
🔥 DB설계<br>
<img width="435" alt="image" src="https://github.com/jua930128/finalProject/assets/133546011/5bde8a0f-c818-4832-986d-b3588e0845cc">


