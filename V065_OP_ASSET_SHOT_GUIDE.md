# NEO-TELHARSA v0.65 — SILENT PARADISE 20컷 제작 가이드

기준: v0.64의 실제 오프닝 구간 시작 시각과 장면 ID. 구간 시간은 음원 타임라인의 장면 경계이며 **보컬 음절 정밀 싱크 보증은 아닙니다.**

## 공통 제작 규칙
- 배경: 1920×1080 WebP (16:9, 중앙 안전 영역 고려). 인물: 투명 PNG 1600×900 또는 세로 전신 PNG. 오버레이: 투명 PNG 1920×1080.
- 캐릭터·효과 이미지는 선택 사항이며, 누락되면 CSS 장면으로 자동 대체됩니다.
- 실제 가사 자막은 게임에서 별도 렌더링합니다. 이미지에는 가사·타이틀 문자를 굽지 마세요.
- 모바일 크롭: 화면 중앙 50~65%에 핵심 피사체를 배치하고 자막·컨트롤 영역을 비워 두세요.
- 다니엘라의 외형은 확정된 정보(안경·수사관)를 우선하며, 미겔 본체·복제체·NANO의 비밀을 드러내지 마세요.
- `assets/opening/op-shot-manifest.json`은 참고용입니다. 경로/위치를 수정할 경우 `index.html` 내 `op64Assets`도 함께 수정해야 합니다.

## 20개 컷별 에셋과 카메라 가이드

### SHOT 01 — INITIALIZING (0.00–11.70초)
- 장면: `signal` · 콘셉트: 추상 전자 신호, 파형과 도시 통신망
- 구도: 중앙 원근형 신호 링, 전경은 비워 두기
- 카메라/연출: 신호 확산·미세 줌; UI가 가사를 가리지 않도록 중앙 하단 여백
- 파일: `shot-01-background.webp`, `shot-01-character.png`, `shot-01-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 02 — NEON CITY (11.70–21.97초)
- 장면: `city` · 콘셉트: 네온 도시의 옥상·골목·고층 빌딩
- 구도: 와이드 원경, 건물의 전·중·후경 분리
- 카메라/연출: 낮은 시점 팬 또는 상공 이동; 자막 하단 대비 확보
- 파일: `shot-02-background.webp`, `shot-02-character.png`, `shot-02-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 03 — PUBLIC HOLOGRAM (21.97–31.77초)
- 장면: `xero` · 콘셉트: 상용 홀로그램 OS XERO의 공개 광고
- 구도: 광고판을 한쪽 1/3에 배치, 인물 정체 비노출
- 카메라/연출: 광고면 클로즈업·가벼운 회전·글리치
- 파일: `shot-03-background.webp`, `shot-03-character.png`, `shot-03-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 04 — DANIELA LEONHARDT (31.77–40.70초)
- 장면: `daniela` · 콘셉트: 안경을 쓴 다니엘라의 수사관 실루엣
- 구도: 측면 또는 로우앵글, 얼굴은 실루엣으로 처리
- 카메라/연출: 인물보다 배경을 느리게 이동해 패럴랙스
- 파일: `shot-04-background.webp`, `shot-04-character.png`, `shot-04-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 05 — CASE OPEN (40.70–49.18초)
- 장면: `investigation` · 콘셉트: 미확인 사건 기록, 증거 카드, 비 내리는 수사 현장
- 구도: 탑뷰 자료 또는 OTS 수사 화면, 단서 내용은 추상화
- 카메라/연출: 기록을 따라 느린 팬·확대, 확인되지 않은 진실 노출 금지
- 파일: `shot-05-background.webp`, `shot-05-character.png`, `shot-05-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 06 — SILENT PARADISE (49.18–68.50초)
- 장면: `title` · 콘셉트: NEO-TELHARSA / SILENT PARADISE 타이틀 배경
- 구도: 중앙 타이틀을 위한 네거티브 스페이스
- 카메라/연출: 비트에 맞춘 줌·스윕, 텍스트 중복 삽입 지양
- 파일: `shot-06-background.webp`, `shot-06-character.png`, `shot-06-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 07 — SLEEPLESS CITY (68.50–82.20초)
- 장면: `city` · 콘셉트: 네온 도시의 옥상·골목·고층 빌딩
- 구도: 와이드 원경, 건물의 전·중·후경 분리
- 카메라/연출: 낮은 시점 팬 또는 상공 이동; 자막 하단 대비 확보
- 파일: `shot-07-background.webp`, `shot-07-character.png`, `shot-07-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 08 — COMMUNICATION (82.20–98.50초)
- 장면: `signal` · 콘셉트: 추상 전자 신호, 파형과 도시 통신망
- 구도: 중앙 원근형 신호 링, 전경은 비워 두기
- 카메라/연출: 신호 확산·미세 줌; UI가 가사를 가리지 않도록 중앙 하단 여백
- 파일: `shot-08-background.webp`, `shot-08-character.png`, `shot-08-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 09 — PUBLIC SYSTEM (98.50–112.70초)
- 장면: `xero` · 콘셉트: 상용 홀로그램 OS XERO의 공개 광고
- 구도: 광고판을 한쪽 1/3에 배치, 인물 정체 비노출
- 카메라/연출: 광고면 클로즈업·가벼운 회전·글리치
- 파일: `shot-09-background.webp`, `shot-09-character.png`, `shot-09-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 10 — CASE FILES (112.70–130.50초)
- 장면: `investigation` · 콘셉트: 미확인 사건 기록, 증거 카드, 비 내리는 수사 현장
- 구도: 탑뷰 자료 또는 OTS 수사 화면, 단서 내용은 추상화
- 카메라/연출: 기록을 따라 느린 팬·확대, 확인되지 않은 진실 노출 금지
- 파일: `shot-10-background.webp`, `shot-10-character.png`, `shot-10-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 11 — HUNTER (130.50–146.80초)
- 장면: `daniela` · 콘셉트: 안경을 쓴 다니엘라의 수사관 실루엣
- 구도: 측면 또는 로우앵글, 얼굴은 실루엣으로 처리
- 카메라/연출: 인물보다 배경을 느리게 이동해 패럴랙스
- 파일: `shot-11-background.webp`, `shot-11-character.png`, `shot-11-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 12 — SILENT PARADISE (146.80–172.50초)
- 장면: `title` · 콘셉트: NEO-TELHARSA / SILENT PARADISE 타이틀 배경
- 구도: 중앙 타이틀을 위한 네거티브 스페이스
- 카메라/연출: 비트에 맞춘 줌·스윕, 텍스트 중복 삽입 지양
- 파일: `shot-12-background.webp`, `shot-12-character.png`, `shot-12-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 13 — NEON / MOTION (172.50–193.50초)
- 장면: `city` · 콘셉트: 네온 도시의 옥상·골목·고층 빌딩
- 구도: 와이드 원경, 건물의 전·중·후경 분리
- 카메라/연출: 낮은 시점 팬 또는 상공 이동; 자막 하단 대비 확보
- 파일: `shot-13-background.webp`, `shot-13-character.png`, `shot-13-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 14 — TRANSMISSION (193.50–210.00초)
- 장면: `signal` · 콘셉트: 추상 전자 신호, 파형과 도시 통신망
- 구도: 중앙 원근형 신호 링, 전경은 비워 두기
- 카메라/연출: 신호 확산·미세 줌; UI가 가사를 가리지 않도록 중앙 하단 여백
- 파일: `shot-14-background.webp`, `shot-14-character.png`, `shot-14-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 15 — FRAGMENTS (210.00–229.00초)
- 장면: `memory` · 콘셉트: 기억을 연상시키는 빛 조각과 노이즈
- 구도: 비대칭 대각선 구도, 인물·관계의 실체 비노출
- 카메라/연출: 조각의 역방향 드리프트·포커스 변화
- 파일: `shot-15-background.webp`, `shot-15-character.png`, `shot-15-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 16 — SIGNAL DETECTED (229.00–246.85초)
- 장면: `signal` · 콘셉트: 추상 전자 신호, 파형과 도시 통신망
- 구도: 중앙 원근형 신호 링, 전경은 비워 두기
- 카메라/연출: 신호 확산·미세 줌; UI가 가사를 가리지 않도록 중앙 하단 여백
- 파일: `shot-16-background.webp`, `shot-16-character.png`, `shot-16-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 17 — SILENT PARADISE (246.85–268.50초)
- 장면: `title` · 콘셉트: NEO-TELHARSA / SILENT PARADISE 타이틀 배경
- 구도: 중앙 타이틀을 위한 네거티브 스페이스
- 카메라/연출: 비트에 맞춘 줌·스윕, 텍스트 중복 삽입 지양
- 파일: `shot-17-background.webp`, `shot-17-character.png`, `shot-17-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 18 — AFTERIMAGE (268.50–285.03초)
- 장면: `city` · 콘셉트: 네온 도시의 옥상·골목·고층 빌딩
- 구도: 와이드 원경, 건물의 전·중·후경 분리
- 카메라/연출: 낮은 시점 팬 또는 상공 이동; 자막 하단 대비 확보
- 파일: `shot-18-background.webp`, `shot-18-character.png`, `shot-18-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 19 — MEMORY / ECHO (285.03–295.20초)
- 장면: `memory` · 콘셉트: 기억을 연상시키는 빛 조각과 노이즈
- 구도: 비대칭 대각선 구도, 인물·관계의 실체 비노출
- 카메라/연출: 조각의 역방향 드리프트·포커스 변화
- 파일: `shot-19-background.webp`, `shot-19-character.png`, `shot-19-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택

### SHOT 20 — SIGNAL REMAINS (295.20–304.78초)
- 장면: `outro` · 콘셉트: 잔류 신호와 어두워지는 도시
- 구도: 중앙에 작은 광점, 화면 가장자리 어둡게
- 카메라/연출: 움직임 감소, 마지막 신호 소멸
- 파일: `shot-20-background.webp`, `shot-20-character.png`, `shot-20-overlay.png`
- 권장 레이어: 배경 필수 아님 / 인물 선택 / 오버레이 선택
