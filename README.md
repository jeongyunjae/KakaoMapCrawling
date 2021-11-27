# KakaoMapCrawling

- selenium을 활용항 카카오맵 데이터 크롤링 기능입니다.

## 기능

- "서울 또는 경기도의 시,군 데이터 + 검색하고자하는 키워드"를 카카오맵 검색항목으로 하여 모든 검색결과를 csv파일에 저장합니다.

## 사용법

- python3 설치
- pip3 install -r requirements.txt
- kakaoMapCrawling.py파일 실행

## 주의사항

- 현재 컴퓨터에 설치된 크롬버전에 맞는 chromedriver가 프로젝트 폴더에 존재햐아 합니다.(포함된 크롬드라이버 버전: 96.0.4664.55)

-chromedriver 설치 url: https://chromedriver.chromium.org/downloads

- kakaoMapCrawling.py에 존재하는 chromedriver_path변수에 해당 크롬드라이버 파일 위치를 표시해야합니다.

- 만일 코드가 동작하지 않는다면, 카카오맵 내부 html요소가 변경되었을 가능성이 있으므로, 해당 검색 페이지에 F12버튼을 눌러 개발자도구를 켜 해당 html요소를 확인하여 변경사항을 체크합니다.
