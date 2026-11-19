# 내 도시 기준 세계 여행지 날씨 비교기

## 기능
- 기준 도시(성남·서울·부산·제주) 선택
- 전 세계 도시 검색(Open-Meteo Geocoding API)
- 여행지 3곳 비교
- 선택한 날짜의 실제 일별 예보(최고·최저기온, 강수확률, 날씨 상태)
- 기온과 강수확률을 고려한 참고용 여행지 추천
- 반응형 스카이블루·화이트·딥네이비 디자인

## 데이터 및 이용 조건
- 날씨: Open-Meteo Forecast API
- 도시 검색: Open-Meteo Geocoding API
- API 키 없이 브라우저에서 직접 호출합니다.
- 무료 API는 비상업적 이용 조건을 따릅니다. 상업적 이용 전 Open-Meteo에 별도 문의하세요.
- 데이터 출처 표기를 페이지 하단에 포함했습니다.
- 최대 16일 예보 범위 안에서만 날짜를 선택할 수 있습니다. 실제 데이터가 제공되지 않는 도시/날짜는 오류로 표시합니다.

## GitHub Pages 배포
1. GitHub 계정에 로그인합니다.
2. 우측 상단 `+` → `New repository`를 누릅니다.
3. Repository name에 `world-weather-compare`를 입력합니다.
4. `Public`을 선택하고 `Create repository`를 누릅니다.
5. `Add file` → `Upload files`를 선택합니다.
6. 이 프로젝트의 `index.html` 파일을 업로드합니다.
7. `Commit changes`를 누릅니다.
8. 저장소의 `Settings` → 왼쪽 `Pages`로 이동합니다.
9. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
10. Branch는 `main`, 폴더는 `/(root)`를 선택하고 `Save`를 누릅니다.
11. 잠시 기다린 뒤 Pages 화면에 표시되는 공개 주소를 엽니다.
   보통 `https://사용자아이디.github.io/world-weather-compare/` 형식입니다.

## 수정
`index.html`을 수정해 다시 업로드하거나 GitHub에서 직접 편집하면 됩니다.

## 참고
이 프로젝트는 정적 웹사이트입니다. 서버나 API 키를 저장하지 않습니다. 브라우저가 Open-Meteo에 직접 요청합니다.
