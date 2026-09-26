# 영어 말하기 수행평가 연습장

GitHub Pages에 바로 올릴 수 있는 단일 페이지 버전입니다.

## 올리는 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`과 `.nojekyll`을 저장소 루트에 업로드합니다.
3. 저장소에서 **Settings → Pages**로 이동합니다.
4. **Build and deployment → Source**를 `Deploy from a branch`로 선택합니다.
5. Branch를 `main`, Folder를 `/(root)`로 선택하고 Save 합니다.
6. 잠시 기다리면 GitHub Pages 주소가 생성됩니다.

## 마이크 권한

GitHub Pages는 HTTPS로 열리기 때문에 Chrome/Edge에서 마이크 권한을 사이트별로 저장할 수 있습니다.

처음 한 번 `허용`한 뒤에도 계속 묻는다면:
- 주소창 왼쪽의 사이트 정보 아이콘 클릭
- 사이트 설정
- 마이크 → 허용

## 파일 구조

- `index.html` : 전체 웹앱
- `.nojekyll` : GitHub Pages에서 그대로 배포되도록 하는 빈 파일
