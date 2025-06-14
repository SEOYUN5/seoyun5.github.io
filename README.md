⭐이 포트폴리오는 저의 개발 도전을 기록하고, 다양한 웹 프로젝트를 한눈에 보여줘 동기부여를 받기 위해 제작되었습니다.⭐

GitHub Pages: https://seoyun5.github.io

GitHub Repository: https://github.com/SEOYUN5/seoyun5.github.io

테마: Start Bootstrap의 Freelancer 테마 (https://startbootstrap.com/theme/freelancer)

나의 스킬
C, Java, JavaScript, CSS, Git, SQL, Rust: 학습 중

프로젝트 (5개)
1.개인 포트폴리오 웹사이트 (완료)
설명: Freelancer 테마를 활용한 HTML/CSS 기반 포트폴리오 사이트
배포: GitHub Pages

2.Chat Server (예정)
설명: Python 소켓 프로그래밍 기반 채팅 서버 (닉네임, 접속자 목록, 방송 기능)

3.Login System (예정)
설명: HTML/JavaScript와 LocalStorage를 활용한 사용자 인증 시스템

4.Online Shop Backend (예정)
설명: Java 또는 Python으로 구현하는 쇼핑몰 백엔드 서버 (상품 조회, 장바구니, 주문 처리)

5. Cloud Storage Front-end (예정, 학습 중)
설명: HTML/JavaScript로 구현하는 클라우드 업로드 인터페이스

Database 연결 (예정)
HTML/JavaScript로 구현하는 클라우드 업로드 인터페이스

희망 직무: 
백엔드 개발자: 사용자는 보지 못하더라도, 백엔드는 서비스의 핵심 엔진으로 작동하여 큰 성취감을 줄 것같다.

추가 기능 ()
1. 언어 토글 (EN/KO)
설명: 사이트 내 모든 텍스트를 한국어와 영어로 전환합니다. 상단 내비게이션 바에 위치한 EN/KO 버튼 클릭 시 .lang-ko와 .lang-en 클래스를 가진 요소들의 display 속성을 토글하여 언어를 변경합니다.
코드 위치:
HTML: index.html 파일 (GitHub 경로: main/index.html)
JS: js/scripts.js 파일 (GitHub 경로: main/js/scripts.js), window.addEventListener('DOMContentLoaded', ...) 콜백 내부 하단
코드 설명: 버튼 클릭 이벤트 리스너를 등록하여 언어별 클래스 요소를 querySelectorAll로 수집한 뒤, style.display를 none 또는 inline으로 설정합니다.

2. 추천 노래 버튼. 추천 노래 버튼
설명: "추천 노래!" 버튼 클릭 시 유튜브 재생 목록을 새 탭으로 엽니다.
코드 위치:
HTML: index.html의 About 섹션(<section id="about">) 내 .text-center 영역에 위치한 <a class="btn btn-outline-light btn-lg" ...>
코드 설명: <a> 태그에 href="https://www.youtube.com/watch?v=...", target="_blank", rel="noopener", title="Go to Recommended Song" 속성을 설정하여 새 탭으로 안전하게 이동하도록 구현하였습니다.

3. 이메일 팝오버
설명: 이메일 아이콘 클릭 시 말풍선 형태의 팝오버로 이메일 주소를 표시합니다.
코드 위치:
HTML: index.html 푸터 섹션(<footer class="footer text-center">) 내 Social Icons 컬럼 안에 <button id="email-btn" data-bs-toggle="popover" ...>
JS: js/scripts.js 파일, 동일한 DOMContentLoaded 콜백 내부, 언어 토글 코드 바로 아래에 위치
코드 설명: Bootstrap의 Popover 클래스를 호출하여 data-bs- 속성이 설정된 요소를 초기화합니다. 클릭 시 data-bs-content 값으로 지정된 이메일 주소가 팝오버로 나타납니다.

4. Instagram 링크
설명: Instagram 아이콘 클릭 시 개인 프로필 페이지로 이동합니다.
코드 위치:
HTML: index.html 푸터 섹션 Social Icons 컬럼 내 <a href="https://www.instagram.com/..." class="btn btn-outline-light btn-social">
코드 설명: <a> 태그의 href 속성에 인스타그램 프로필 URL을 넣어 클릭 시 해당 페이지로 이동하도록 하였습니다.
