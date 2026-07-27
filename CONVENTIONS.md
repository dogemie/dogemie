# 📁 GitHub Repository Naming Conventions

## 1. General Rules
* **kebab-case 사용:** 모든 이름은 소문자로 작성하며, 띄어쓰기 대신 하이픈(`-`)을 사용합니다.
* **간결함과 명확성:** 범용적으로 통용되는 약어(예: qml, qec, 3dgs, rl 등)를 적극 활용하여 길이를 줄입니다.
* **언어/프레임워크 종속성:** 특정 프레임워크에 강하게 종속된 프로젝트의 경우 이름에 포함합니다. (예: `pennylane`, `pytorch`, `qiskit`)

## 2. Naming Format
저장소 이름은 기본적으로 다음 구조를 따릅니다.
> **`[category]-[topic]-[description]`**

### Categories (분류 접두사)
저장소의 목적을 가장 먼저 알 수 있도록 아래의 접두사 중 하나를 선택하여 시작합니다.

* **`research-`** : 학술 연구, 논문 구현, 새로운 알고리즘 테스트
  * *ex) `research-vqc-reinforcement-learning`*
  * *ex) `research-qldpc-error-correction`*

* **`project-`** : 공식적인 팀 프로젝트, 졸업 작품 등 완성도 있는 결과물
  * *ex) `project-3dgs-env-reconstruction`*

* **`study-`** : 학습 목적의 코드, 튜토리얼, 스터디 자료
  * *ex) `study-pennylane-tutorials`*
  * *ex) `study-quantum-winter-school`*

* **`archive-`** : 학회 발표 자료, 세미나 문서, 단체 활동 기록 등 보관용
  * *ex) `archive-kqis-2026-poster`*
  * *ex) `archive-quantum-society-docs`*

* **`tool-`** : 유틸리티 스크립트, 트러블슈팅, 게임 모드 및 환경 설정 파일
  * *ex) `tool-rimworld-mod-manager`*
  * *ex) `tool-git-lfs-scripts`*
 
* **`course-`** : 대학교 전공 및 교양 수업 실습, 과제용 저장소
  * **패턴:** `course-[과목코드]-[과목명]` (과목 코드는 소문자로 통일)
  * *ex) `course-ite2023-data-structure`*
  * *ex) `course-cs101-introduction`*

* **`side-`** : 공식적인 프로젝트(`project-`)로 부르기에는 가벼운 개인 프로젝트나 아이디어 스케치
  * *ex) `toy-quantum-calculator`*
  * *ex) `side-pennylane-visualizer`*

* **`legacy-`** : 과거에 진행하다가 중단되었거나, 더 이상 유지보수하지 않는(Deprecated) 프로젝트
  * *ex) `legacy-old-qec-model`*
  * *ex) `legacy-vqc-test-env`*

* **`personal-`** : 개인적인 일상, 자산 관리, 차량 유지보수, 개인 일정 등 라이프스타일 및 자가 관리 시스템
  * *ex) `personal-management-system`*
  * *ex) `personal-lifelog-hub`*
