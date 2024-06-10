# git_study

[Git 기본 명령어]

git 저장소 생성
git init

현재 상태 확인
git status

커밋에 파일 변경 사항을 한번에 모두 포함
git add -A

커밋 생성
git commit -m "작성할 커밋 내용"

전체 로그 확인 
git log

[Git Branch 관련]

브랜치 생성
git branch [브랜치명]

해당 브랜치로 이동
git checkout [브랜치명]

브랜치 생성하고 해당 브랜치로 바로 이동
git branch -b [브랜치명]

원하는 브랜치로 이동했는지 확인
git branch

브랜치 삭제
git branch -d [브랜치명]

현재 브랜치에 다른 브랜치 수정사항 병합
git merge [다른 브랜치 이름]