---
title: OSS 팀 프로젝트, 개인 활동 계획
author: devquint
show_author_profile: true
tags: OSS_Practice
---

# OSS 팀 프로젝트 활동 계획

## 프로젝트 선정 및 조사

이전에 작성된 [프로젝트 진행사항 정리](https://devquint.github.io/2020/05/24/project-proceed.html) 포스트를 참고해주세요.
대규모 추가(`PR #53`)가 있었지만 주요 메인테이너가 아닌 커뮤니티의 참여는 오타 수정, 간단한 내용 추가, Convention 관련 개선 등의 내용이 있었습니다.


## 팀 활동 방향

이전에 작성된 [프로젝트 개선사항 정리](https://devquint.github.io/2020/05/24/team-plan.html) 포스트를 참고해주세요.
`python-for-beginners` 위주로 오타 및 convention 수정, 코드 및 주석 개선, 문서 한글 번역 작업을 진행하려고 하였습니다.


### 팀 활동 계획

다른 커뮤니티 멤버의 기여로 일정을 구체적으로 정할 시 흔들릴 우려가 있기에 개략적인 순서만 정하였습니다.

다음 순서로 진행합니다.
1. 이미 발견된 Issue 해결, 추가적인 Issue 생성 후 해결
1. 기존 코드, 주석 등을 다듬는 등 개선 작업
1. 각종 문서 및 코드 한글화 작업
1. 팀원이 커밋하는 코드에 대한 코드 리뷰는 상시 진행


## 개인별 활동 방향

### 타 팀원 활동 방향

상술한 순서대로 활동을 진행하며, 개인의 능력과 선호에 따라서 원하는 활동을 진행하되 상호 간 코드 리뷰, 피드백을 추가적으로 진행하기로 하였습니다.

상세한 내용은 [팀 정적 페이지의 개인별 역할 분담 포스트](https://20-1-skku-oss.github.io/2020-1-OSS-2/2020/05/24/Individual-Role.html)를 참고해 주세요.
개략적인 내용은 아래와 같습니다.

* 강성민
	* `python-for-beginners`의 신규 문서 작성
	* 동료 코드 리뷰
	* `more-python-for-beginners`의 다듬기 및 번역 작업
* 김도열
	* Issue `#3`, `#6` 해결
	* `more-python-for-beginners` 관련 검증, 다듬기 및 번역 작업
* 서채연
	* `python-for-beginners`의 다듬기, 피드백, 오류 수정 및 번역 작업
* 이종윤
	* `python-for-beginners`의 다듬기 작업
	* `python-for-beginners`의 `Slides` 다듬기 및 번역 작업
* 정현태
	* `python-for-beginners`의 `Slides` 내의 `Leading Zero` 제거
	* `python-for-beginners`의 `README.md`들 다듬기 및 번역 작업


### 개인 활동 방향

어느 정도의 파이썬 지식이 있고, 다른 프로그래밍 언어의 경험이 팀원들에 비해 많은 편이기에 코드 리뷰 활동과 더불어 `more-python-for-beginners`의 작업을 진행하는 방향으로 결정하였습니다.
더불어 팀장으로서 Github 관련 관리, 프로젝트 진행 관리 또한 진행할 계획입니다.

세부적인 활동 계획은 아래와 같습니다.

* 팀 활동
	* 팀 Github 정적 페이지 총괄 관리
	* Git 사용 시 Conflict 관련 처리 주도
	* 이외 여러 잡다한 일들
* 프로젝트 활동
	* 팀원의 커밋들에 대한 (코드 )리뷰 진행
		* typo, (coding )convention 등 확인
		* 문법적 오류 확인
		* 더 나은 코드 제안
	* `python-for-beginners` 문서 작성
		* `01` 폴더가 `Slides`에는 있으나 프로젝트에는 없어 혼란을 주고 있음
		* 관련 부분을 명확히 하고, 내용 보충 측면에서 해당 부분 문서 작성
		* VS Code 사용 관련 내용
	* `more-python-for-beginners` 피드백
		* 해당 내용을 학습하며 피드백 제안
		* 학습자의 입장에서 어렵거나 헷갈리는 부분 Issue 작성
		* 만약 수정할 수 있으면 수정하여 Pull Request