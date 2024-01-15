---
layout: post
published: true
title: "How to write commit messages"
excerpt: Git commit message 작성시 참고 사항
date:  2024-01-24 10:34:00 +0900
tags: [github, commit, memos]
comments: true
---

Git Commit시 message 작성할 때마다 나름 열심히 뭔가를 적어서 올렸다. 
그러나 한참 지난 다음에 커밋 히스토리를 찾아볼 때 딱히 유용한 정보가 되지 못하는 경우가 다반사. 
이대로는 안되겠다 싶어 찾아보니, 역시나 일반적으로 적용되는 규칙이 있었다. 

### 일반적인 규칙

- 제목 첫 글자는 대문자, 50자 이내, 마침표 사용 안함

- 제목은 명령문으로 작성, 과거형 사용하지 않음

- 본문의 각 행은 72자 이내로, 줄바꿈 사용하여 내용 구분

- 본문은 어떻게 보다 **무엇을, 왜**에 대하여 설명


### 자주 쓰는 말머리

- feat: 기능구현, 새로운 기능 추가, 기존의 기능을 요구 사항에 맞추어 수정

- refactor: 기능의 변화가 아닌 코드 리팩터링 ex. 변수 이름 변경

- test: 테스트 추가, 테스트 리팩토링

- docs: 문서 수정 ex. README.md

- style: 코드포맷, 세미콜론 누락 등 코드 수정이 없는 경우

- fix: 기능에 대한 버그 수정

- !BREAKING CHANGE: API 변경 ex.API의 매개변수, 반환값 변경

- rename: 파일, 패키지명 수정

- remove: 파일 삭제

- comment: 주석 관련

- build : 빌드 관련 수정

- chore: 그 외 자잘한 수정

- release : 버전 릴리즈