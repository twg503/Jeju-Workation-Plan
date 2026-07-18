# Jeju-Workation-Plan GitHub 작업 안내

이 문서는 다른 컴퓨터에서도 제주 워케이션 지도를 수정하고 GitHub Pages에 반영하기 위한 안내서입니다.

## 저장소와 배포 주소

- GitHub 저장소: https://github.com/twg503/Jeju-Workation-Plan
- 모바일·웹 지도: https://twg503.github.io/Jeju-Workation-Plan/
- 기본 브랜치: `master`
- Pages 배포 위치: `master` 브랜치의 `/(root)`
- 실제 지도 파일: `JEJU.html`
- 사이트 진입 파일: `index.html`

`master` 브랜치에 변경 사항을 올리면 GitHub Pages가 자동으로 다시 배포됩니다. 반영에는 보통 몇 분이 걸릴 수 있습니다.

## 권장 방법: GitHub Desktop 사용

### 1. 처음 한 번만 설정하기

1. https://desktop.github.com/ 에서 GitHub Desktop을 설치합니다.
2. GitHub Desktop을 실행하고 `twg503` 계정으로 로그인합니다.
3. `File → Clone repository`를 선택합니다.
4. `twg503/Jeju-Workation-Plan`을 선택합니다.
5. 해당 컴퓨터에서 저장할 폴더를 지정하고 `Clone`을 누릅니다.

다운로드한 폴더 안의 파일을 수정해야 합니다. 다른 곳에 따로 복사한 오래된 파일을 수정하면 최신 변경 내용을 덮어쓸 수 있습니다.

### 2. 수정하기 전에 최신 파일 받기

1. GitHub Desktop에서 `Jeju-Workation-Plan` 저장소를 선택합니다.
2. 상단의 `Fetch origin`을 누릅니다.
3. `Pull origin` 버튼이 나타나면 반드시 눌러 최신 변경 내용을 받습니다.

여러 컴퓨터에서 작업할 때는 항상 수정 전에 이 과정을 먼저 진행합니다.

### 3. 지도 수정하기

1. 내려받은 저장소 폴더의 `JEJU.html`을 편집합니다.
2. 파일을 저장합니다.
3. 가능하면 PC 브라우저에서 `JEJU.html`을 열어 화면과 기능을 확인합니다.

지도 내용만 바꿀 때는 대부분 `JEJU.html`만 수정하면 됩니다. `index.html`은 웹 주소에서 `JEJU.html`을 열어주는 진입 파일이므로 일반적으로 수정할 필요가 없습니다.

### 4. GitHub에 올리기

1. GitHub Desktop의 왼쪽 변경 파일 목록을 확인합니다.
2. `Summary`에 변경 내용을 간단히 적습니다. 예: `제주 활동 장소 추가`
3. `Commit to master`를 누릅니다.
4. 상단의 `Push origin`을 누릅니다.

`Commit`만 하고 `Push origin`을 누르지 않으면 GitHub와 웹사이트에는 반영되지 않습니다.

### 5. 배포 확인하기

1. `Push origin` 후 1~5분 정도 기다립니다.
2. https://twg503.github.io/Jeju-Workation-Plan/ 을 엽니다.
3. 이전 화면이 나오면 강력 새로고침을 합니다.
   - Windows: `Ctrl + Shift + R`
   - macOS: `Command + Shift + R`
   - 모바일: 페이지를 새로고침하거나 시크릿 탭에서 확인

## GitHub 웹사이트에서 직접 업로드하는 방법

GitHub Desktop을 설치하지 않아도 파일 하나를 교체할 수 있습니다.

1. https://github.com/twg503/Jeju-Workation-Plan 에 로그인합니다.
2. 저장소의 `JEJU.html`을 선택합니다.
3. 우측 상단의 연필 아이콘으로 직접 편집하거나 `Add file → Upload files`를 선택합니다.
4. 수정된 `JEJU.html`을 업로드합니다.
5. 변경 설명을 적고 `Commit changes`를 누릅니다.

웹 업로드를 사용하더라도 먼저 저장소의 최신 `JEJU.html`을 내려받아 수정하는 것이 안전합니다.

## 여러 컴퓨터에서 작업할 때 지켜야 할 순서

1. 작업 시작 전 `Fetch origin → Pull origin`
2. 파일 수정 및 확인
3. `Commit to master`
4. `Push origin`

한 컴퓨터에서 수정한 뒤 Push하지 않거나, 다른 컴퓨터에서 Pull하지 않고 수정하면 변경 내용이 충돌하거나 이전 파일로 덮어쓸 수 있습니다.

## 충돌이 표시될 때

GitHub Desktop에서 `conflict` 또는 `merge conflict`가 표시되면 무작정 덮어쓰지 않습니다. 두 컴퓨터에서 같은 부분을 수정했을 가능성이 있습니다. 필요한 변경 내용을 비교한 뒤 하나로 합쳐야 합니다. 판단이 어렵다면 파일을 추가로 수정하거나 Push하지 말고 도움을 요청합니다.

## 계정과 보안 주의사항

- GitHub 비밀번호, 인증 코드, 개인 액세스 토큰을 HTML이나 이 문서에 적지 않습니다.
- 공용 컴퓨터에서는 작업 후 GitHub Desktop과 브라우저에서 로그아웃합니다.
- 저장소가 공개 상태이므로 업로드한 파일은 누구나 볼 수 있습니다.
- 개인 연락처, 비밀번호, 비공개 API 키를 저장소에 올리지 않습니다.

## 문제가 생겼을 때 확인할 것

- GitHub 저장소에 수정 시각과 파일 내용이 실제로 바뀌었는지 확인합니다.
- GitHub Desktop에서 `Push origin`까지 완료했는지 확인합니다.
- 저장소의 `Settings → Pages`가 `master`와 `/(root)`로 설정되어 있는지 확인합니다.
- 웹사이트 반영이 늦으면 저장소의 `Actions` 탭에서 Pages 배포 상태를 확인합니다.
- 지도 마커는 보이는데 배경만 안 보이면 지도 타일 서버 또는 네트워크 차단 문제일 수 있습니다.
