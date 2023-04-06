# Git_Github TIL
- 당일 학습한 내용을 정리합니다.

## 2023-03-27
- git bash 설치
- 기초 리눅스 명령어
- vim 사용법

## 2023-03-28
- commit
  - 개념
  - 언제 커밋을 만드는지
  - 커밋 크기
- 저장소(리포)
  - 개념
  -일반 폴더와 저장소의 차이
  - `git init` 명령어로 저장소 만들기

## 2023-03-29
- 커밋 만들기
  - `git commit -m`
- 스테이징 영역
  - `git add` 명령어로 커밋에 포함시키고 싶은 파일만 스테이징 영역에 추가

## 2023-04-04
- 커밋 수정하기
  - 로컬에서 수정하려면 `git rebase -i HEAD~(숫자)` 후, pick->reword
  - 이미 push한 경우, `git --force origin main`을 사용
    - `force`는 기존 커밋을 뒤집어 쓰기 때문에 신중하게 사용
- 이슈 지우기
  - 커밋 메시지에서 이슈번호(#n) 앞에 특정어를 붙이면 이슈를 지울 수 있음
    - 특정어 : fix, fixed, fixes, close ...
- `git stash` 커밋하지 않고 변경내역을 로컬에 임시 저장
- `git branch` 브랜치 목록을 출력
- `git log` 커밋내역을 출력
  - `git log --oneline`, `git shortlog` 로 간단하게 출력가능
- `git status` 파일의 변경 내역 등을 출력

## 2023-04-07 
  - 스테이지에서 내리기
    - `git reset` // 최근 파일 내리기
    - `git reset` 파일 경로 // 경로 상 파일 내리기
