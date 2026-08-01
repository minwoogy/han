# POL-SEARCH GPS 기록기 v0.2

GitHub Pages 배포용 정적 웹앱입니다.

## 배포
1. GitHub에서 새 Public 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`, `.nojekyll`, `README.md`를 저장소 최상위에 업로드합니다.
3. 저장소 `Settings` → `Pages`
4. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
5. Branch는 `main`, Folder는 `/(root)`로 선택하고 Save 합니다.
6. 잠시 후 표시되는 `https://사용자명.github.io/저장소명/` 주소로 접속합니다.

## 시험
- Chrome에서 위치 권한을 허용합니다.
- `현재 위치 1회 확인`으로 GPS를 먼저 확인합니다.
- `수색 시작` 후 실외에서 이동합니다.
- 종료 후 GPX, GeoJSON 또는 CSV를 저장합니다.

## 주의
브라우저가 백그라운드로 전환되거나 화면이 꺼지면 위치기록이 중단될 수 있습니다.
현장 운용형은 안드로이드 백그라운드 위치 서비스가 필요합니다.
