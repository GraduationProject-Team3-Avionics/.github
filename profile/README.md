# 🎓 Graduation Project Team 3 — Avionics

Welcome to our graduation project repository!  
We are **Team 3 — Avionics**, developing an autonomous drone system consisting of **Perception**, **Control**, and **Interface** modules.

---

## 📂 Our Repositories

| Module        | Description                             | Link |
|---------------|-------------------------------------------|------|
| Navigation | Object detection, environment sensing      | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/Perception.git) |
|  Control     | Flight control & trajectory planning        | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/Control.git) |
|  Interface   | User interface & mission management         | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/Interface.git) |

---

## Simulation Environment

Before testing in the real world,  
we run our drone in a **PX4-Gazebo Simulation** environment.

- PX4-Autopilot (customized for our project):  
  [PX4-Autopilot_ASP Repository](https://github.com/imhyeonwoo/PX4-Autopilot_ASP.git)

---

## Project Structure Overview

```
Avionics Team
├── Perception   # Detect environment & Visual Odometry/SLAM
├── Control      # Control Algorithms & Flight Logics
└── Interface    # Custom Msgs & Gazebo Setup
```

---

<p align="center">
  <img src="https://github.com/GraduationProject-Team3-Avionics/.github/blob/main/docs/in%20case%20of%20fire.png" width="400">
</p>

---

<details>
<summary><b><span style="font-size: 1.4em">📄GIT Commit Rule</span></b></summary>

| 타입        | 설명                                                                                         | 사용 시기                                              | 예시 커밋 메시지                              |
|-------------|--------------------------------------------------------------------------------------------|---------------------------------------------------------|---------------------------------------------|
| **feat**    | 새로운 기능을 추가하거나, 기존 기능을 요구사항에 맞춰 확장·변경할 때 사용합니다.              | 신규 화면·API·컴포넌트 개발, 사용자 요구 기능 반영 시     | `feat: 이메일 인증 기능 추가`                |
| **fix**     | 코드가 의도한 대로 동작하지 않는 버그를 수정할 때 사용합니다.                                | 크래시, 예외 처리 누락, 잘못된 화면 표시 등 문제 발생 시 | `fix: 로그인 버튼 클릭 시 무한 로딩 현상 해결` |
| **build**   | 프로젝트 빌드 설정 변경이나 의존성 추가·제거, 배포 스크립트 수정 등에 사용합니다.            | `package.json` 변경, Webpack/Gulp 설정 수정 등          | `build: webpack 프로덕션 모드 설정 추가`     |
| **chore**   | 코드 동작과 무관한 환경 설정·잡무를 처리할 때 사용합니다. (예: `.gitignore` 수정)             | 문서·코드 이외 파일 정리, 의존성 버전 업데이트 등        | `chore: .gitignore에 로그 파일 패턴 추가`     |
| **ci**      | CI/CD 파이프라인 설정을 변경할 때 사용합니다. (예: GitHub Actions, Jenkins)                 | 자동화 테스트, 린트, 배포 워크플로우 추가·수정 시        | `ci: GitHub Actions에 린트 및 테스트 단계 추가` |
| **docs**    | 코드 주석이나 프로젝트 문서(README, 위키, API 문서 등)만 수정할 때 사용합니다.               | 가이드 추가·오타 수정·문서 구조 변경 시                  | `docs: README에 설치 가이드 추가`             |
| **style**   | 코드 기능엔 영향 없는 포맷팅·스타일(들여쓰기, 공백, 세미콜론 등)을 변경할 때 사용합니다.       | Prettier/ESLint 적용, 코드 포맷팅 통일 시                | `style: Prettier로 코드 포맷팅 적용`           |
| **refactor**| 기능(로직)은 그대로 두고, 내부 구조나 가독성을 높이기 위해 코드 구조·이름만 정리할 때 사용합니다.| 함수·변수명 변경, 모듈 분리·병합, 중복 제거 등           | `refactor: userService 함수명 변경 및 모듈 분리` |
| **test**    | 테스트 코드(유닛·통합)를 새로 추가하거나, 기존 테스트를 수정·보완할 때 사용합니다.             | 테스트 커버리지 추가, 테스트 실패 수정 시                | `test: 로그인 서비스 유닛 테스트 추가`         |
| **release** | 새로운 버전을 릴리즈하거나, 태그를 관리할 때 사용합니다.                                     | 버전 태그 생성, 배포 노트 작성 시                        | `release: v1.2.0`                             |


- feat (기능) : 새로운 기능을 추가
- fix(수정) : 버그를 수정
- refactor(리팩터링) : 코드를 재구성/최적화
- docs(문서) : 문서를 업데이트 할 때
- chore(작업) : 빌드 시스템, 패키지 관련 또는 구성 변경과 같은 작업 수행
- style(스타일) : 코드 스타일, 들여쓰기, 공백 및 포맷팅과 관련된 변경사항
- test(테스트) : 테스트를 추가하거나 수정, 리팩터링 한 경우
- perf(성능) : 성능 향상ㅇ을 위한 변경사항을 나타냄
- revert(되돌리기) : 이전 커밋을 취소함

</details>

---
