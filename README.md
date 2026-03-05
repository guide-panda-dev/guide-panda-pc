<p align="center">
  <img src="https://github.com/user-attachments/assets/6f8a7246-1f63-41d5-acc3-49d8d75363de" alt="GuidePanda Logo" width="120" />
</p>

<h1 align="center">GuidePanda</h1>

<p align="center">
  <strong>Path of Exile 빌드 가이드 데스크탑 앱</strong><br>
  액트별 지도 · 가이드 · 패시브 트리를 한 화면에
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.9.1-orange" alt="version" />
  <img src="https://img.shields.io/badge/platform-Windows%20x64-blue" alt="platform" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/03492b06-193e-425a-bb7e-5e63b3571201" alt="GuidePanda 메인 화면" width="900" />
</p>

---

## 소개

**GuidePanda**는 Path of Exile (PoE1) 액트 진행 빌드 가이드를 데스크탑에서 편리하게 열람·편집할 수 있는 Windows 전용 앱입니다.

액트별 진행 지도, 스킬 가이드, 패시브 트리 이미지를 **3패널 레이아웃**으로 동시에 표시하며, 창 크기에 따라 자동으로 반응형 레이아웃이 전환됩니다.

### 주요 기능

- **6종 프리셋 빌드** 내장 (Act 1 ~ 엔드게임까지)
- **3패널 동시 보기** — 지도 / 가이드 / 패시브를 한 화면에
- **반응형 레이아웃** — 넓은 화면(3패널) · 중간(토글) · 좁은 화면(탭 전환)
- **패시브 트리 드로잉** — 이미지 위에 직접 경로 표시 (Ctrl+Z 지원)
- **인라인 편집** — 젬 타입/이름, 가이드 텍스트, 패시브 테이블 편집
- **사용자 빌드 생성** — 나만의 빌드 가이드 작성
- **내보내기/가져오기** — 빌드를 폴더 단위로 백업·공유
- **포터블 모드** — 설치 없이 exe와 같은 폴더에 데이터 저장

---

## 다운로드 및 실행

### 포터블 버전 (권장)

1. [Releases](https://github.com/guide-panda-dev/guide-panda-pc/releases) 페이지에서 최신 `GuidePanda-v0.9.1-portable.zip` 다운로드
2. 원하는 위치에 압축 해제
3. `GuidePanda.exe` 실행

> 포터블 모드에서는 exe와 같은 폴더의 `guide-panda-data/` 에 사용자 데이터가 저장됩니다.
> USB 등에 복사해 다른 PC에서도 동일한 환경으로 사용할 수 있습니다.

### 시스템 요구사항

- **OS**: Windows 10/11 (64비트)
- **디스크**: ~200MB (이미지 포함)
- **추가 설치**: 불필요 (Electron 런타임 내장)

---

## 내장 빌드 목록

| 빌드 | 클래스 | 범위 |
|------|--------|------|
| **라이트닝 애로우 (LA)** | Deadeye | Act 1~10 + Mapping |
| **종말의 낙인 (AB_Eli)** | Elementalist | Act 1~5 + 엔드게임 |
| **화산탄 지뢰 (HBM_Sabo)** | Trickster | Act 1~5 + 엔드게임 |
| **지면분쇄 (VFS_Berserker)** | Berserker | Act 1~7, 10 + 엔드게임 |
| **면죄/SRS (BAMA_Guardian)** | Guardian | Act 1~6 + 엔드게임 |
| **정의의 화염 (RF_Cft)** | Chieftain | Act 1~5 + Mapping |

---

## 스크린샷

### 홈 화면

내장된 프리셋 빌드와 사용자 빌드를 카드 형태로 한눈에 확인할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8feb50f0-8cb5-476e-a5e5-616359bab7c4" alt="홈 화면" width="700" />
</p>

### 빌드 인트로 페이지

빌드 소개, 난이도/예산 등 성능 지표, 장단점을 확인할 수 있습니다. 물론 편집도 가능합니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc139e84-2bf6-43d7-b87d-179060d32629" alt="인트로 페이지" width="700" />
  <br>
  <img src="https://github.com/user-attachments/assets/c93033a9-4c65-4655-a946-6fa6bb21665f" alt="인트로 페이지(편집)" width="500" />
  <br>

</p>

### 3패널 와이드 레이아웃

지도 · 가이드 · 패시브 트리를 동시에 표시합니다. 패널 경계선을 드래그해 비율을 조절할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/03492b06-193e-425a-bb7e-5e63b3571201" alt="3패널 와이드 레이아웃" width="900" />
</p>

### 패시브 트리 드로잉

패시브 트리 이미지 위에 직접 경로를 그릴 수 있습니다. `Ctrl+Z`로 실행취소가 가능합니다.

<p align="center">
   <img src="https://github.com/user-attachments/assets/8e5181c5-37ab-41a4-8304-0bf65f4b1b29" alt="패시브 트리 드로잉" width="500" />
  
</p>

### 가이드 편집 모드

가이드 텍스트를 직접 편집하고, 젬 배지·시맨틱 태그를 버튼 하나로 삽입할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0110bc80-546b-4b10-98ca-f49e6abfad6e" alt="가이드 편집 모드" width="400" />
  
</p>

### 엑스트라/메모 페이지

빌드별로 최대 3개의 추가 메모 페이지를 생성해 자유롭게 활용할 수 있습니다.

<p align="center">
   <img src="https://github.com/user-attachments/assets/55de0cec-6d2c-4624-9a58-832bb9853b80" alt="메모 페이지" width="900" />
</p>

### 좁은 화면 (탭 전환 모드)

창 너비가 좁으면 Map / Guide / Passive 탭으로 전환되는 반응형 레이아웃을 제공합니다.

<p align="center">
    <img src="https://github.com/user-attachments/assets/4be2c385-3873-466b-9005-395beedb76cc" alt="좁은 화면 탭 전환" width="350" />
</p>

### 빌드 내보내기 / 환경설정

빌드를 폴더 단위로 내보내거나, 패널 비율·글자 크기 등을 세부 조정할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/59781f19-75b5-4b86-ba77-6c35f5c8cf0e" alt="빌드 내보내기" width="350" />
  &nbsp;&nbsp;&nbsp;&nbsp;
    <img src="https://github.com/user-attachments/assets/d86a06da-5f2a-4402-b063-fe94588298ca" alt="환경설정" width="350" />

</p>

---

## 사용법

### 주요 조작

| 동작 | 방법 |
|------|------|
| 빌드 선택 | 홈 화면에서 빌드 카드 클릭 |
| 액트 이동 | 좌측 사이드바에서 액트 번호 클릭 |
| 패널 크기 조절 | 패널 경계선 드래그 |
| 패시브 트리 드로잉 | 패시브 이미지에서 마우스 드래그 |
| 드로잉 실행취소 | `Ctrl + Z` |
| 가이드 편집 | 편집 모드 진입 후 텍스트 수정 |
| 글자 크기 조절 | 설정(톱니바퀴) → 글자 크기 슬라이더 |
| 빌드 내보내기 | 홈 → 빌드 카드 메뉴 → 내보내기 |
| 빌드 가져오기 | 홈 → 가져오기 버튼 |

### 젬 배지 표기

가이드 텍스트에서 스킬 젬은 색상 배지로 표시됩니다:

- `[g 젬이름]` — 녹색 (Dexterity 젬)
- `[r 젬이름]` — 빨간색 (Strength 젬)
- `[b 젬이름]` — 파란색 (Intelligence 젬)

---

## 기술 스택

### 핵심 프레임워크

| 기술 | 버전 | 역할 |
|------|------|------|
| [Electron](https://www.electronjs.org/) | 40.6.1 | 데스크탑 앱 프레임워크 |
| [React](https://react.dev/) | 19.2.0 | UI 라이브러리 |
| [Vite](https://vite.dev/) | 7.3.1 | 빌드 도구 및 개발 서버 |
| [TypeScript](https://www.typescriptlang.org/) | 5.9.3 | 정적 타입 시스템 |
| [Tailwind CSS](https://tailwindcss.com/) | 4.2.1 | 유틸리티 기반 스타일링 |

### 빌드 및 배포

| 도구 | 버전 | 역할 |
|------|------|------|
| [electron-builder](https://www.electron.build/) | 26.8.1 | 앱 패키징 (NSIS / Portable) |
| [Cheerio](https://cheerio.js.org/) | 1.2.0 | HTML → JSON 파서 (빌드 데이터 변환) |
| ESLint | 9.39.1 | 코드 린트 |

### 아키텍처 개요

```
┌─────────────────────────────────────────────┐
│               Renderer (React)              │
│  React 19 + Vite + Tailwind CSS             │
│  window.electronAPI.* 로만 IPC 접근          │
├─────────────── preload.cjs ─────────────────┤
│  contextBridge: 12개 API 노출               │
│  contextIsolation: true                     │
├─────────────────────────────────────────────┤
│             Main Process (Node.js)          │
│  IPC 핸들러 6종 + 커스텀 프로토콜            │
│  파일 I/O · 다이얼로그 · userData 관리        │
└─────────────────────────────────────────────┘
```

### 데이터 구조

- **프리셋 빌드**: 앱에 내장된 6종 빌드 (읽기전용)
- **사용자 빌드**: `guide-panda-data/builds/` 에 JSON으로 저장
- **오버라이드**: 프리셋 수정 시 원본은 유지하고 변경분만 별도 저장

### 보안

| 설정 | 값 | 설명 |
|------|-----|------|
| `nodeIntegration` | `false` | 렌더러에서 Node.js 직접 접근 차단 |
| `contextIsolation` | `true` | 메인/렌더러 프로세스 완전 격리 |
| Preload | `contextBridge` | 허용된 API만 선별 노출 |

---

### 빌드 및 배포


포터블 zip 배포 시에는 빌드 결과물의 `win-unpacked/` 폴더를 zip으로 압축합니다.

---

## 버전 히스토리

### v0.9.5 (현재)
- 젬 색상 버튼 순서를 r, g, b, w로 통일
- 가이드 패널 액트 변경 시 스크롤 위치 초기화
- 지도 패널 편집 강화 — 행 이동, 웨이포인트 토글, 필드 편집
- 패시브 패널 젬 추가를 단일 버튼으로 간소화
- 스킬 패널 젬 순서 이동 및 카테고리 UI 개선
- REGEX 글자수 기본값 250으로 조정
- 인트로 레이더 차트 추가 및 퍼포먼스 레이아웃 개선

### v0.9.4
- 패시브 패널 편집 기능 강화 — 테이블/푸터 가져오기, 행/젬 순서 이동
- REGEX 복사 시 글자수 제한 적용 + 초과 저장 시 안내 모달

### v0.9.3
- 스킬 패널 — 다른 액트에서 가져오기 및 카테고리 순서 이동
- 패시브 패널 편집 중 탭 전환 경고 모달 추가
- export/import 시 extraPages 이미지 및 maps.json 누락 수정

### v0.9.2
- 패시브 푸터 통합 및 편집 기능 강화
- 가이드 젬 배지 선택 감싸기 및 헤더 동적 버전 표시
- 패시브 푸터 UI 개선 — textarea 전환 및 색상 구분 강화

### v0.9.1
- 버전 번호 표시 추가
- 패시브 편집 버튼 사라짐 버그 수정
- 패시브 패널 젬 타입/이름 인라인 편집
- 편집 중 이탈 방지 및 삭제 확인 모달

### v0.9.0
- 포터블 배포 지원
- IPC 오류 처리 강화
- 빌드 임포트/익스포트
- 패시브 트리 드로잉 (Ctrl+Z)
- 인트로 페이지 Performance 섹션
- 6종 프리셋 빌드 번들 완성

---

## 라이선스

MIT License

---

<p align="center">
  <sub>Made for Path of Exile community</sub>
</p>
