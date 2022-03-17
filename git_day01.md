오늘 배웠던 내용에 대해 md파일로 작성

# Git 명령어
- pwd : 현재 디렉토리 경로
- mkdir : '폴더' 생성. ex) mkdir test : test라는 폴더 생성해라
- cd : change directory. 경로 이동
    - 절대경로 : cd /c/Users/LG/바탕화면
    - 상대경로 : cd .. (상위경로로 이동) / cd . (현재경로)
- touch : 파일 생성. ex) touch a.txt : a.txt라는 파일 생성해라
- ls : list segments
    - 해당 디렉토리 안 파일들의 리스트를 보여라
    - ls -a : 숨김파일까지 전부 보여주는 옵션
    - ls -l : 확장자 등 모든 정보 표시
- rm : remove
    - 대상 삭제. ex) rm a.txt : a.txt 파일 삭제해라
    - 폴더 삭제 불가 : -r 옵션 사용
    - rm -r : 재귀적으로 폴더 하단 내역도 삭제
    - rm -rf : 강제로 삭제. 사용 지양할 것
    - 사용 시 휴지통에도 남아있지 않게되니 주의. 되도록 GUI 환경에서 삭제할 것
- ctrl+l : 스크롤 내림
- 화살표 위, 아래 : 이전 라인 가져오기
-mv : move. 
    - mv 대상파일 변경이름 : 이름 변경하라. (이동 지시한 디렉토리 없는 경우)
    - mv 대상파일 이동위치 ex) practice.txt CLI/ : practice.txt 파일을 CLI 폴더로 옮겨라
