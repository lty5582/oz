# Calculator Project

🎉 **Calculator Project**는 HTML, CSS, JavaScript를 이용해 간단한 계산기 기능을 구현한 웹 애플리케이션입니다. 기본적인 사칙연산 및 다양한 스타일링 기능을 포함하여 사용자에게 직관적이고 간편한 계산 경험을 제공합니다.

## 📝 목차

- [프로젝트 소개](#프로젝트-소개)
- [설치 및 실행 방법](#설치-및-실행-방법)
- [기능 설명](#기능-설명)
- [브랜치 전략](#브랜치-전략)
- [기여 방법](#기여-방법)
- [라이선스](#라이선스)

## 프로젝트 소개

이 프로젝트는 기본적인 계산 기능을 구현하는 예제 웹 애플리케이션으로, 다음과 같은 주요 기능을 포함합니다:

- 사칙연산 (덧셈, 뺄셈, 곱셈, 나눗셈)
- 숫자 및 연산자 입력
- 결과 계산 및 오류 처리
- 버튼 hover 효과 및 특수 버튼 스타일링

프론트엔드 기술만을 이용하여 계산기를 구축하였으며, 주로 자바스크립트를 활용하여 기능을 구현했습니다.

## 설치 및 실행 방법

이 프로젝트는 간단한 정적 웹 애플리케이션이므로, 로컬 환경에서 쉽게 실행할 수 있습니다.

1. **프로젝트 클론**:
   ```bash
   git clone https://github.com/your-username/calculator-project.git
   cd calculator-project

2. **파일 실행:**:
   - `index.html` 파일을 브라우저에서 열어 계산기를 실행합니다.

## 기능 설명

### 기본 계산 기능

- **숫자 및 연산자 입력**: 버튼을 통해 숫자와 사칙연산 기호를 입력할 수 있습니다.
- **화면 초기화 (AC)**: 모든 입력값을 지우고 화면을 초기화합니다.
- **마지막 입력 삭제 (DEL)**: 마지막으로 입력된 문자를 지웁니다.
- **결과 계산**: `=` 버튼을 눌러 입력된 수식의 결과를 계산합니다.

### 오류 처리 기능

- 잘못된 수식이 입력될 경우, `Error` 메시지가 화면에 표시되어 사용자에게 오류를 알려줍니다.

### 스타일링 기능

- **버튼 hover 효과**: 버튼에 마우스를 올리면 색상이 변경되어 사용자에게 시각적 피드백을 제공합니다.
- **특수 버튼 스타일링**: `AC`, `DEL` 등의 특수 버튼은 색상을 다르게 설정하여 주요 기능을 강조합니다.

## 동작 화면
![계산기 실행](https://github.com/user-attachments/assets/88aacacb-9d1e-43c0-b2fa-99e4ad0aace1)

## 브랜치 전략

이 프로젝트는 **Git Flow**에 기반하여 `main`과 `develop` 브랜치를 사용해 관리합니다.

- **main**: 안정적인 코드를 유지하고 배포 가능한 버전을 포함합니다.
- **develop**: 기능이 개발되고 테스트되는 브랜치입니다.
- **feature 브랜치**: 각 기능 추가 시 생성되며, 완료 후 `develop`에 병합됩니다.

### 개발 브랜치 목록

- `feature/calculate-function`: 기본 계산 기능 추가
- `feature/error-handling`: 오류 처리 기능 추가
- `feature/button-styling`: 버튼 hover 및 특수 버튼 스타일링 추가
