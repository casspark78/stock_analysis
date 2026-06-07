# Obsidian 설정 가이드

## 1단계 — Obsidian 설치

- Mac: https://obsidian.md 에서 다운로드
- iPhone: App Store에서 "Obsidian" 검색 후 설치

---

## 2단계 — Vault 생성 (iCloud에)

1. Obsidian 실행 → **Create new vault**
2. Vault name: `daily-log`
3. Location: **iCloud Drive** 폴더 선택
4. Create

> iPhone에서도 같은 Vault가 자동으로 보여요.

---

## 3단계 — 플러그인 설치

설정(⚙️) → Community plugins → Browse

### 필수 설치
| 플러그인 | 용도 |
|----------|------|
| **Templater** | 날짜 자동 입력 템플릿 |
| **Calendar** | 날짜별 노트 달력 뷰 |

---

## 4단계 — Templater 설정

설정 → Templater
- Template folder: `templates`
- **Trigger Templater on new file creation**: ON

---

## 5단계 — Daily Notes 설정

설정(⚙️) → Core plugins → Daily notes → ON

- Date format: `YYYY-MM-DD`
- New file location: `daily`
- Template file: `templates/daily`

---

## 6단계 — 이 폴더의 파일 복사

이 저장소의 `obsidian-vault/` 폴더 안 파일들을
Vault 폴더(`iCloud Drive/Obsidian/daily-log/`)에 복사하세요.

```
daily-log/          ← Vault 루트
  templates/
    daily.md
    weekly.md
```

---

## 매일 사용 방법

- **Mac**: 리본 메뉴의 📅 아이콘 클릭 → 오늘 날짜 클릭
- **iPhone**: 하단 메뉴 → Open today's daily note

오늘 파일이 없으면 템플릿으로 자동 생성돼요.
