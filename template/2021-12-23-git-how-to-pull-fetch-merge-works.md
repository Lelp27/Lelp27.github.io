---
title:  "[Git] pull / fetch로 원격 저장소 변경 사항 로컬에 반영하기 | pull, fetch, merge 차이"
excerpt: "Git 기본 명령어 정리 (3) pull, fetch, merge / 프로젝트 변경 사항 pull, fetch, merge하여 반영하기"

categories:
  - Git
tags:
  - [Git]

permalink: /git/how-to-pull-fetch-merge-works/

toc: true
toc_sticky: true
 
date: 2021-12-22
last_modified_at: 2021-12-22
published : false
---

**Git Bash 기준으로 정리. GitHub Desktop을 이용한 방법은 여기로 > [GitHub 시작하기 - Repository 생성, clone, commit, push](https://choiiis.github.io/git/basics-of-clone-commit-push/)**

# clone과 remote의 차이
두 단어의 사전적 정의를 보면 알 수 있다.
>`clone` (동) 복제하다
>
>`remote` (형) 원격의

`clone` : GitHub repository에 있는 내용을 내 로컬(컴퓨터)에 '복제'하는 명령어다. 즉, repository에 있는 파일을 내 로컬의 특정 디렉토리로 가져올 수 있다.

`remote` : 내 로컬의 데이터를 '원격의' 저장소에 연결하는 것이다. 여기서 원격 저장소는 GitHub repository이고, '연결'만 하는 것이기 때문에 pull이나 push를 해줘야 데이터를 원격 저장소로 보내거나 가져올 수 있다.

결국 clone은 remote를 한 다음에 pull을 하는 것과 같은 역할을 한다고 할 수 있다.

# clone으로 repository 데이터 가져오기


# remote로 repository와 연결하기

# git remote에 대해서 좀더 알아보자
## 연결된 원격 저장소 확인하기

## 원격 저장소 변경하기

# init으로 git 초기 설정하기
> Create an empty Git repository or reinitialize an existing one. This command creates an empty Git repository - basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template files.

출처: [https://git-scm.com/docs/git-init](https://git-scm.com/docs/git-init)

