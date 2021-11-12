# 명령어 (command) 정리
git (명령어) --help 라고 검색시 사용법 페이지가 나온다.
 
## Github 업로드 방법
1) 코드를 작성한다.
2) git status
    현재 상태를 확인한다. (추가 예정 파일이 빨간 색으로 명기되어 있음을 확인한다.)
3) git add .
    작성한 코드를 git에 추가한다.
4) git status
    add가 되었는지 확인한다. (준비된 파일이 초록색으로 명기되어 있음을 확인한다.)
5) git commit -m "메세지"
    git에 커밋한다. (메세지 : 작업 내용)
6) git push origin main(master)
    git 저장소에 commit한 내용을 반영한다.
    업로드 된 상태를 확인한다. (done.)