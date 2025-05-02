1장
git config user.name '' 깃 환경 이름 저장
git config user.email '' 메일 저장

pwd 	현재 경로 표시
ls 	현재 디렉터리 안의 내용 표시
ls -l	현재 디렉터리 안의 파일과 폴더 상세 정보 표시
cd..	부모 디렉터리로 이동
ls -a	현재 디렉터리 안의 숨긴 파일과 숨긴 디렉터리 표시
clear	 화면 클리어
cd 풀더명	지정한 하위 디렉터리로 이동
mkdir		새 디렉터리 생성
cd~	홈 디렉터리로 이동
rm	파일이나 디렉터리 삭제
exit	터미널 종료

2장
git init	현재 위치에 지역 저장소 생성
git status	깃 상태확인
git add ~	파일을 스테이지에 올리기
git commit	-m ""	스테이징한 파일을 커밋 메시지를 붙여 커밋
git commit -am ""	메시지를 붙여 스테이징과 커밋 동시에 하기
git log	커밋 정보를 확인
git diff	최근 버전과 작업 폴더의 수정 파일 사이의 차이를 보여줌
git restore 파일명		작업트리에서 '파일명'의 수정 내용을 취소
git restore --staged '파일명'	'파일명'의 스테이징을 취소
git reset HEAD^	가장 최근 커밋을 취소
git reset 커밋 해시	지정한 커밋해시로 이동하고 이후 커밋은 취소
git revert 커밋 해시	지정한 커밋 해시의 변경 이력을 취소

3장
git branch '이름' 새로운 브랜치를 만들기
git log --oneline 커밋 로그에서 한 줄에 한 커밋씩 표시
git switch '이름' 해당 브랜치로 전환
git add . 수정한 파일을 스테이지에 한꺼번에 올리기
git log --branches --graph 커밋 로그에 각 브랜치의 커밋을 그래프로 표시
git merge '파일명' 현재 main 브랜치에 있으며 '파일명' 브랜치를 main 브랜치에 병합
git branch -d '파일명' '파일명' 브랜치 삭제
git cherry-pick '해시' 현재 main 브랜치에 있으며 커밋 해시 '해시'를 체리픽으로 병합
touch '파일명' '파일명'이라는 빈 파일을 만들기

4장
git remote add origin 저장소 주소 원격 저장소에 연결
git remot -v 원격 저장소에 연결됐는지 확인
git push -u origin main 지역 저장소의 커밋을 맨 처음 원격 저장소로 올리기
git push(push origin main) (한번 올린 후에)지역 저장소의 커밋을 맨 처음 원격 저장소로 올리기
git pull(pull origin main) 원격 저장소의 커밋을 지역 저장소로 가져오기
ssh-keygen SSH 키 만들기

5장
git clone 저장소 주소 . 원격 저장소를 '저장소 주소'라는 지역 저장소로 복제합니다
git pull 원격 저장소의 최신 커밋을 가져옴
git fetch 원격 저장소의 커밋을 가져오기만 하고 병합하진 않기
git diff HEAD origin/main 페치로 가져온 정보와 최신 커밋의 차이를 살펴보기
풀 리퀘스트(PR) -> 협업 저장소에 커밋을 올리고 리뷰를 위한 메시지를 남기는것
