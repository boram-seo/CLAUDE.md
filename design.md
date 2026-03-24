# Design System — 관리자페이지 v1.0

> **출처**: Figma — 디자인시스템 출입통제시스템 v1.0
> **대상**: 관리자페이지 (Admin Page)
> **버전**: v1.0 (디자인 시스템 변경 시 본 문서도 함께 업데이트 필요)
> **최종 수정**: 2026-03-24

---

## 목차

1. [폰트 (Typography)](#1-폰트-typography)
2. [색상 (Color)](#2-색상-color)
3. [형태 (Shape / Border Radius)](#3-형태-shape--border-radius)
4. [고도 (Elevation / Shadow)](#4-고도-elevation--shadow)
5. [레이아웃 (Layout)](#5-레이아웃-layout)
6. [사용 원칙](#6-사용-원칙)

---

## 1. 폰트 (Typography)

### 기본 서체
| 항목 | 값 |
|------|-----|
| **Font Family** | `Pretendard` |
| **지원 Weight** | Regular(400), SemiBold(600), Bold(700) |

---

### 1-1. Display
> 화면에서 가장 큰 텍스트. 주로 배너 등 마케팅 용도. 자유롭게 변형 가능하나 과도한 크기 사용 지양.

| Style | Size (PC) | Font Weight | Line Height | Letter Spacing |
|-------|-----------|-------------|-------------|----------------|
| display-large | 60px | 700 (Bold) | 150% | 1px |
| display-medium | 44px | 700 (Bold) | 150% | 1px |
| display-small | 36px | 700 (Bold) | 150% | 1px |

---

### 1-2. Heading
> 페이지 단위의 타이틀과 모듈 단위 역할 강조에 사용.

| Style | Size (PC) | Size (Mobile) | Font Weight | Line Height | Letter Spacing |
|-------|-----------|---------------|-------------|-------------|----------------|
| heading-xlarge | 40px | 28px | 700 (Bold) | 150% | 1px |
| heading-large | 32px | 24px | 700 (Bold) | 150% | 1px |
| heading-medium | 24px | 22px | 700 (Bold) | 150% | 0px |
| heading-small | 19px | 19px | 700 (Bold) | 125% | 0px |
| heading-xsmall | 17px | 17px | 700 (Bold) | 125% | 0px |
| heading-xxsmall | 15px | 15px | 700 (Bold) | 125% | 0px |

---

### 1-3. Body
> 본문 및 서브타이틀(헤딩 보조) 용도.

| Style | Size (PC) | Font Weight | Line Height | Letter Spacing |
|-------|-----------|-------------|-------------|----------------|
| body-large-bold | 19px | 700 (Bold) | 125% | 0px |
| body-medium-bold | 17px | 700 (Bold) | 125% | 0px |
| body-small-bold | 15px | 700 (Bold) | 125% | 0px |
| body-xsmall-bold | 13px | 700 (Bold) | 125% | 0px |
| body-large-semibold | 19px | 600 (SemiBold) | 125% | 0px |
| body-medium-semibold | 17px | 600 (SemiBold) | 125% | 0px |
| body-small-semibold | 15px | 600 (SemiBold) | 125% | 0px |
| body-xsmall-semibold | 13px | 600 (SemiBold) | 125% | 0px |
| body-large-regular | 19px | 400 (Regular) | 125% | 0px |
| body-medium-regular | 17px | 400 (Regular) | 125% | 0px |
| body-small-regular | 15px | 400 (Regular) | 125% | 0px |
| body-xsmall-regular | 13px | 400 (Regular) | 125% | 0px |

---

## 2. 색상 (Color)

> 색상 체계는 기업이미지와 일관된 시각적 경험 유지를 위해 구성.
> 정보의 계층과 우선순위를 시각적으로 구분하며, 유저의 행동을 유도.

---

### 2-1. Gray (그레이)
> 중립적인 색상으로 주로 배경, 텍스트, 구분선에 사용.

| Token | Hex | 주요 용도 |
|-------|-----|-----------|
| gray-5 | `#f6f6f6` | 배경, 비활성 영역 |
| gray-10 | `#e6e7e9` | 구분선, 테두리 |
| gray-20 | `#d3d6d9` | 비활성 테두리 |
| gray-30 | `#b9c1c9` | 플레이스홀더 |
| gray-40 | `#a4acb3` | 보조 텍스트 |
| gray-50 | `#7f8a93` | 비활성 텍스트 |
| gray-60 | `#5e6770` | 서브 텍스트 |
| gray-70 | `#484f57` | 보조 아이콘 |
| gray-80 | `#32353c` | 기본 아이콘 |
| gray-90 | `#23262a` | 다크 배경 |
| gray-95 | `#121214` | 가장 어두운 배경 |

---

### 2-2. Primary (프라이머리 — 기본 모드)
> 기업의 상징성을 나타내며 인터페이스에서 가장 주목받는 요소.
> 중요도 높은 액션이나 정보 강조에 사용.

| Token | Hex | 주요 용도 |
|-------|-----|-----------|
| primary-5 | `#e6edff` | 배경 강조 |
| primary-10 | `#c3d4ff` | 호버 배경 |
| primary-20 | `#8fafff` | 라이트 포인트 |
| primary-30 | `#6d96ff` | 보조 포인트 |
| primary-40 | `#4c76ff` | 약한 강조 |
| **primary-50** | **`#2943f9`** | **메인 Primary** |
| primary-60 | `#1536db` | 호버 상태 |
| primary-70 | `#0a26b3` | 프레스 상태 |
| primary-80 | `#061262` | 강한 강조 |
| primary-90 | `#001b3b` | 페이지 헤더, 네비게이션 |
| primary-95 | `#000f21` | 가장 어두운 Primary |

---

### 2-3. Secondary (세컨더리 — 기본 모드)
> Primary 색상을 서포트하는 보조 역할.
> 중요도가 낮은 액션 표시, 구분을 위한 배경으로 사용.

| Token | Hex | 주요 용도 |
|-------|-----|-----------|
| secondary-5 | `#f3f3ff` | 배경 강조 |
| secondary-10 | `#e0e1ff` | 라이트 배경 |
| secondary-20 | `#c7caff` | 보조 배경 |
| secondary-30 | `#abafff` | 라이트 포인트 |
| secondary-40 | `#9886ff` | 보조 포인트 |
| **secondary-50** | **`#735bf9`** | **메인 Secondary** |
| secondary-60 | `#5b40f2` | 호버 상태 |
| secondary-70 | `#4611af` | 프레스 상태 |
| secondary-80 | `#300072` | 강한 강조 |
| secondary-90 | `#230053` | 딥 퍼플 |
| secondary-95 | `#160036` | 가장 어두운 Secondary |

---

### 2-4. Accent (강조색)
> 사용자가 주목해야 하는 특정 상태/이벤트/알림 요소에만 사용 (전체 UI의 **5% 이하**).
> 정보 우선순위를 시각적으로 부각. 제한적 사용으로 시각적 과부하 방지.

| Token | Hex | 주요 용도 |
|-------|-----|-----------|
| accent-5 | `#fff5f2` | 배경 알림 |
| accent-10 | `#ffd8cc` | 라이트 강조 배경 |
| accent-20 | `#fec6b5` | 보조 강조 |
| accent-30 | `#ffb098` | 라이트 포인트 |
| accent-40 | `#fb9272` | 보조 포인트 |
| **accent-50** | **`#ff6f43`** | **메인 Accent (오렌지)** |
| accent-60 | `#f84f1b` | 호버 상태 |
| accent-70 | `#b23406` | 프레스 상태 |
| accent-80 | `#862d07` | 강한 강조 |
| accent-90 | `#5e1904` | 딥 오렌지 |
| accent-95 | `#3d0e00` | 가장 어두운 Accent |

---

### 2-5. System Colors (시스템 색상)

#### Danger (위험/오류)
| Token | Hex |
|-------|-----|
| danger-5 | `#ffe2e2` |
| danger-10 | `#ffcfcf` |
| danger-20 | `#ffacac` |
| danger-30 | `#ff7373` |
| danger-40 | `#e94c4c` |
| **danger-50** | **`#ce2727`** |
| danger-60 | `#af1919` |
| danger-70 | `#a30000` |
| danger-80 | `#700000` |
| danger-90 | `#4a0000` |
| danger-95 | `#2c0000` |

#### Warning (경고)
| Token | Hex |
|-------|-----|
| warning-5 | `#fff3db` |
| warning-10 | `#ffe0a3` |
| warning-20 | `#ffc95c` |
| warning-30 | `#ffb114` |
| warning-40 | `#c78500` |
| **warning-50** | **`#9e6a00`** |
| warning-60 | `#8a5c00` |
| warning-70 | `#614100` |
| warning-80 | `#422c00` |
| warning-90 | `#2e1f00` |
| warning-95 | `#241800` |

#### Success (성공)
| Token | Hex |
|-------|-----|
| success-5 | `#eaf6ec` |
| success-10 | `#d8eedd` |
| success-20 | `#a9dab4` |
| success-30 | `#7ec88e` |
| success-40 | `#3fa654` |
| **success-50** | **`#228738`** |
| success-60 | `#267337` |
| success-70 | `#285d33` |
| success-80 | `#1f4727` |
| success-90 | `#122b18` |
| success-95 | `#0e2012` |

---

### 2-6. Graphic Colors (그래픽 색상)
> 데이터 시각화(차트, 그래프, 인포그래픽) 및 배너/일러스트 요소에 사용.

| 계열 | Token | Hex |
|------|-------|-----|
| Blue | graphic-blue-0 | `#d4d5ea` |
| Blue | graphic-blue-5 | `#b2b4e2` |
| Blue | graphic-blue-10 | `#8e91d3` |
| Blue | graphic-blue-20 | `#686cc5` |
| Blue | graphic-blue-30 | `#404491` |
| Red | graphic-red-40 | `#ffeef0` |
| Red | graphic-red-50 | `#f6c3ca` |
| Red | graphic-red-60 | `#f08997` |
| Red | graphic-red-70 | `#e85467` |
| Red | graphic-red-80 | `#b51127` |

---

### 2-7. 주요 UI 색상 참고
| 용도 | 색상 | Hex |
|------|------|-----|
| 페이지 헤더 배경 | primary-90 | `#001b3b` |
| 기본 텍스트 | — | `#131416` |
| 보조 텍스트 | — | `#464c53` |
| 라이트 배경 | — | `#f4f5f6` |
| 다크 배경 | — | `#1e2124` |
| 다크 텍스트 (on dark) | — | `#e6e8ea` |

---

## 3. 형태 (Shape / Border Radius)

> 형태는 브랜드의 시각적 아이덴티티를 표현하는 중요한 요소.
> **표준형**: 2px~12px 범위 사용 (신뢰감·안정감·친근함 표현).
> **최대값**: 12px (과도한 둥근 형태 방지).
> 완전한 원형이 필요한 경우 `radius-max` 토큰 사용.

| Level | Container Size | Radius | 적용 컴포넌트 |
|-------|---------------|--------|--------------|
| **xsmall** | 8×8 ~ 16×16px | **2px** | 인디케이터, 뱃지, 프로그레스 바 |
| **small** | 20×20 ~ 32×32px | **4px** | Chips, Checkbox, Radio Button, Switch, Tag |
| **medium** | 40×40 ~ 56×56px | **6px** | Button, Text Input, Textarea, Select, Pagination |
| **medium** | 56×56 ~ 64×64px | **8px** | Button(large), Step Indicator, Carousel |
| **large** | 72×72 ~ 80×80px | **10px** | Card, Dialog |
| **xlarge** | 96×96 ~ 120×120px | **12px** | Banner, Bottom Sheet |

---

## 4. 고도 (Elevation / Shadow)

> 고도(Elevation)는 UI 요소들이 서로 다른 시각적 레벨에 위치하도록 하여 깊이감과 계층 구조를 부여.
> 그림자는 기본 모드에서 특히 효과적이며, 선명한 모드에서는 표면 밝기와 함께 사용.

### 그림자 단계 (Shadow Levels)
| Level | 용도 |
|-------|------|
| Level 1 | 미세한 깊이감 (카드, 기본 컨테이너) |
| Level 2 | 중간 깊이감 (드롭다운, 팝오버) |
| Level 3 | 강한 깊이감 (모달, 다이얼로그) |
| Level 4 | 최대 깊이감 (토스트, 오버레이) |

### 모드별 배경색
| 모드 | 배경색 |
|------|--------|
| 기본 모드 (Light) | `#f4f5f6` |
| 선명한 화면 모드 (Dark) | `#1e2124` |

---

## 5. 레이아웃 (Layout)

> 스타일가이드_레이아웃 프레임에 정의됨.
> *(추후 Figma 레이아웃 프레임 상세 분석 후 업데이트 예정)*

---

## 6. 사용 원칙

### ✅ DO
- Primary 색상은 가장 중요한 CTA(Call to Action) 버튼 및 핵심 정보에만 사용
- Accent 색상은 전체 UI 중 **5% 이하**로 제한 사용
- 동일 계층 컴포넌트에는 동일한 Border Radius 레벨 적용
- 타이포그래피는 정의된 스케일(heading/body) 외 임의 크기 사용 금지
- 어두운 배경 위 텍스트는 `#e6e8ea` 이상의 밝은 색상 사용 (명도 대비 확보)

### ❌ DON'T
- Border Radius **12px 초과** 사용 금지 (완전한 원형 제외)
- Danger/Warning/Success 색상을 시스템 상태 외의 일반 UI에 사용 금지
- Graphic 색상을 주요 UI 인터랙션 요소에 사용 금지 (데이터 시각화 전용)
- Display 타이포그래피를 일반 본문 텍스트에 사용 금지

---

## 변경 이력

| 버전 | 날짜 | 내용 |
|------|------|------|
| v1.0 | 2026-03-24 | 최초 작성 (Figma 디자인시스템 v1.0 기반) |

---

> ⚠️ **주의**: 본 문서는 관리자페이지 v1.0 디자인 시스템 기준입니다.
> 디자인 시스템 변경(v2.0 이상) 시 Figma 파일을 재참조하여 본 문서를 업데이트해 주세요.
