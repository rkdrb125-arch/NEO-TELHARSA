# NEO-TELHARSA v0.66 — 본편 + 오프닝 배경 적용

원본: 사용자 제공 backgrounds_01-07.zip (총 8 PNG: 도시 원본·픽셀 포함).

## 본편 대응
- city-night.webp / xero-square.webp: bg_01_neon_city_original.png (프롤로그, EP.1)
- dawn-crime-scene.webp: bg_02_crime_scene.png (EP.2)
- slum-alley.webp: bg_03_slum_alley.png (EP.3 초입)
- covered-alley.webp: bg_04_dark_alley.png (EP.3 골목)
- abandoned-house.webp: bg_05_abandoned_interior.png (EP.3 폐가 내부)
- house-door.webp: bg_06_warehouse_door.png (EP.3 출입문)
- rainy-house-exterior.webp: bg_07_warehouse_exterior.png (EP.3 외부)

## 오프닝 대응
20개 shot-XX-background.webp 이미지가 제공된 8장 중 장면에 맞는 배경을 선택해 채워졌습니다.
01/07/08은 도시 픽셀 버전을 사용합니다. 모든 샷의 전경 캐릭터·효과 PNG는 미제공 상태로 기존 CSS 실루엣/연출이 유지됩니다.

## 호환성
index.html, MP3, 가사 타임코드, 저장 키, 기존 JS와 모든 문서 파일을 변경하지 않았습니다. 이미지 파일만 추가했습니다. 기존 JS의 이미지 실패 시 CSS 폴백도 유지됩니다.
원본 PNG는 assets/backgrounds/source/ 에 보관합니다.

## 검사
node --check로 index.html 내 인라인 스크립트 문법 검사. ZIP testzip 검증. 주요 파일 SHA256 비교.
실제 모바일 브라우저에서의 시각적 검증은 별도 필요합니다.
