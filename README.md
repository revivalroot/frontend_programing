- 로컬에서 github -repository로 올리기

순서

1. .gitignore 먼저 작성 (지금 폴더에 node_modules/, dist/가 보여서 필수)
node_modules/
dist/
2. git init
3. git add . (gitignore 적용 후 필요한 파일만 스테이징됨)
4. git commit -m "Initial commit"
5. GitHub 웹사이트에서 빈 저장소 생성 (README/gitignore 추가 없이 완전히 빈 상태로)
6. git remote add origin <저장소 URL>
7. git branch -M main
8. git push -u origin main

- repository에서 로컬로 받을때

1. 프로젝트를 받을 위치로 이동 (예: cd D:\)
2. git clone https://github.com/revivalroot/frontend_programing.git ← 폴더가 생김
3. cd frontend_programing ← 방금 생긴 폴더로 들어감
    1. npm install ← 패키지 설치
4. npm run build ← 빌드
