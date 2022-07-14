### local repository의 자료를 github repository로 전송하기

### In Github

1. 기본 브랜치를 master로 변경하기
2. new repository 만들기
    1. 이름 설정
    2. 만들기

### In Local Repository

- 새로운 디렉토리 생성
    - mkdir
    - cd 경로
    - git init
    - git remote add origin (URL)
    - git remote : origin 추가된것 확인
    - touch README.md
        - 내용수정(optional)
- 버전 남기기(commit이 있어야만 push가능)
    - git add(파일명.확장자 파일명.확장자) / git add .
    - git commit -m “message”
    - git push origin master