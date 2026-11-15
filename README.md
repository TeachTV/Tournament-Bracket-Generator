# 🏆 TEACH_TV Tournament Bracket Generator

**토너먼트 대진표 자동 생성기 | Tournament Bracket Generator**

엑셀에서 참가 팀의 순위와 이름을 복사하여 붙여넣으면 토너먼트 대진표를 자동으로 생성할 수 있는 무료 웹 프로그램입니다.

A free web-based tournament bracket generator. Simply copy and paste team rankings and names from Excel to automatically create a tournament bracket.

---

## 🌐 프로그램 실행 | Launch Application

### [🚀 토너먼트 대진표 생성기 실행 / Launch Tournament Bracket Generator](https://teachtv.github.io/Tournament-Bracket-Generator/)

**웹사이트 주소 / Website URL**

https://teachtv.github.io/Tournament-Bracket-Generator/

별도의 설치나 회원가입 없이 웹브라우저에서 바로 사용할 수 있습니다.

No installation or registration is required. Run the application directly in your web browser.

---

## ✨ 주요 기능 | Features

### 📋 1. 엑셀 데이터 붙여넣기 | Excel Copy & Paste

- 엑셀에서 순위와 팀 이름을 복사하여 붙여넣기
- 참가 팀 수에 맞춰 토너먼트 대진표 자동 생성
- 2개부터 최대 256개 팀 지원
- 참가 팀 수가 맞지 않으면 부전승 자동 처리

**English**

- Copy and paste rankings and team names from Excel.
- Automatically generate a tournament bracket.
- Supports 2 to 256 teams.
- Automatically handles byes when necessary.

### 🏆 2. 자동 대진표 생성 | Automatic Bracket Generation

순위를 기준으로 상위 팀과 하위 팀을 매칭합니다.

**64강 예시 / Round of 64 Example**

| 그룹 / Group | 팀 A / Team A | 팀 B / Team B |
|---|---|---|
| 1 | 1위 / Rank 1 | 64위 / Rank 64 |
| 2 | 2위 / Rank 2 | 63위 / Rank 63 |
| 3 | 3위 / Rank 3 | 62위 / Rank 62 |
| ... | ... | ... |
| 32 | 32위 / Rank 32 | 33위 / Rank 33 |

다음 라운드에서도 첫 번째 그룹과 마지막 그룹이 대결합니다.

In each subsequent round, the first group faces the last group.

- 32강: 이전 라운드 1그룹 vs 32그룹
- 16강: 이전 라운드 1그룹 vs 16그룹
- 8강: 이전 라운드 1그룹 vs 8그룹
- 4강: 이전 라운드 1그룹 vs 4그룹
- 결승: 이전 라운드 1그룹 vs 2그룹

### 🎮 3. 경기 결과 및 진행 상태 관리 | Match & Round Management

- 승리 팀 선택 시 다음 라운드 자동 진출
- 그룹별 진행 예정 / 진행 중 / 완료 설정
- 라운드 전체 상태 일괄 변경
- 라운드별 경기 진행률 표시
- 진행 중인 라운드 배경 강조
- 경기 결과 수정 가능

**English**

- Automatically advance winning teams.
- Set individual match statuses: Upcoming, In Progress, or Completed.
- Update all match statuses in a round at once.
- Display round completion progress.
- Highlight active rounds.
- Edit match results.

### 🎨 4. 팀 및 연결선 강조 | Team & Path Highlighting

- 승리 팀의 다음 라운드 연결선 강조
- 특정 팀 선택 및 강조
- 전체 진출 경로 강조
- 마지막 참가 그룹만 강조
- 강조 상태를 이미지 저장에도 반영

**English**

- Highlight winning team connections.
- Select and highlight individual teams.
- Highlight a team's entire tournament path.
- Highlight only the team's latest match group.
- Preserve highlighting in exported images.

### 📊 5. 대진표 표시 범위 설정 | Bracket Display Options

전체 토너먼트를 표시하거나 원하는 라운드부터 표시할 수 있습니다.

예를 들어 128강으로 시작한 대회라도 32강부터 표시하도록 설정할 수 있습니다.

Display the complete bracket or choose a starting round. For example, a tournament that started with 128 teams can be displayed from the Round of 32 onward.

### 📸 6. 이미지 저장 및 복사 | Image Export

- 대진표 전체를 PNG 이미지로 저장
- 대진표 이미지를 클립보드에 복사
- 디스코드 등에서 이미지 공유 가능
- 현재 선택한 라운드 및 강조 상태 반영
- 운영용 설정 버튼은 저장 이미지에서 제외

**English**

- Export the bracket as a PNG image.
- Copy the bracket image to the clipboard.
- Share bracket images on Discord and other platforms.
- Preserve the selected round and highlighting.
- Exclude editing controls from exported images.

### 💾 7. 데이터 저장 및 복원 | Save & Restore

- 브라우저에 진행 상황 자동 저장
- 경기 결과 CSV 다운로드
- 진행 상황 백업 및 복원

**English**

- Automatically save progress in your browser.
- Export match results as CSV.
- Back up and restore tournament data.

---

## 🌍 지원 언어 | Supported Languages

총 **28개 언어**를 지원합니다.

Supports **28 languages**.

| Language | Native Name |
|---|---|
| Korean | 한국어 |
| English | English |
| Japanese | 日本語 |
| Chinese (Simplified) | 简体中文 |
| Chinese (Traditional) | 繁體中文 |
| Portuguese (Brazil) | Português (Brasil) |
| Portuguese (Portugal) | Português (Portugal) |
| Spanish | Español |
| Spanish (Latin America) | Español (Latinoamérica) |
| Italian | Italiano |
| French | Français |
| German | Deutsch |
| Russian | Русский |
| Indonesian | Bahasa Indonesia |
| Thai | ไทย |
| Vietnamese | Tiếng Việt |
| Turkish | Türkçe |
| Arabic | العربية |
| Polish | Polski |
| Ukrainian | Українська |
| Czech | Čeština |
| Hungarian | Magyar |
| Dutch | Nederlands |
| Swedish | Svenska |
| Romanian | Română |
| Hindi | हिन्दी |
| Malay | Bahasa Melayu |
| Filipino | Filipino |

언어를 변경하면 프로그램의 인터페이스와 대진표 상태 표시도 함께 변경됩니다.

Changing the language also updates the interface and bracket status labels.

---

## 📖 사용 방법 | How to Use

**한국어**

1. [토너먼트 대진표 생성기](https://teachtv.github.io/Tournament-Bracket-Generator/)에 접속합니다.
2. 원하는 언어를 선택합니다.
3. 엑셀에서 순위와 팀 이름을 복사합니다.
4. 입력창에 데이터를 붙여넣습니다.
5. 대진표 생성 버튼을 클릭합니다.
6. 경기 결과에 따라 승리 팀을 선택합니다.
7. 필요한 경우 그룹별 진행 상태를 변경합니다.
8. 완성된 대진표를 PNG로 저장하거나 클립보드에 복사합니다.

**English**

1. Open the [Tournament Bracket Generator](https://teachtv.github.io/Tournament-Bracket-Generator/).
2. Select your preferred language.
3. Copy rankings and team names from Excel.
4. Paste the data into the input field.
5. Click Generate Bracket.
6. Select the winning teams as matches are completed.
7. Update match statuses if necessary.
8. Export the bracket as a PNG or copy it to the clipboard.

---

## 💻 실행 환경 | Requirements

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- 기타 최신 웹브라우저

별도의 서버 설치나 프로그램 설치가 필요하지 않습니다.

No additional software installation or server setup is required.

일부 기능은 브라우저의 보안 설정 및 권한에 따라 제한될 수 있습니다.

Some features may be restricted by browser security settings or permissions.

---

## ⚠️ 주의사항 | Important Notes

- 대진표 데이터는 기본적으로 사용자의 브라우저에 저장됩니다.
- 브라우저 데이터를 삭제하면 저장된 진행 상황이 사라질 수 있습니다.
- 중요한 대진표는 백업 기능을 이용해 주세요.
- 클립보드 이미지 복사는 브라우저에 따라 제한될 수 있습니다.
- 여러 사용자의 실시간 공동 편집 기능은 지원하지 않습니다.

**English**

- Tournament data is stored locally in your browser by default.
- Clearing browser data may delete saved progress.
- Use the backup feature for important tournament data.
- Image clipboard functionality may vary depending on the browser.
- Real-time collaborative editing is not supported.

---

## 👨‍💻 제작자 | Developer

**티치TV (TEACH_TV)**

📺 **YouTube:** [@ARIA_TEACH_TV](https://www.youtube.com/@ARIA_TEACH_TV)

🌐 **Tournament Bracket Generator:** https://teachtv.github.io/Tournament-Bracket-Generator/

---

## 📝 오류 제보 및 개선 제안 | Bug Reports & Suggestions

프로그램 사용 중 오류가 발생하거나 개선할 기능이 있다면 GitHub의 Issues를 통해 알려주세요.

If you encounter bugs or have suggestions for improvement, please submit an issue on GitHub.

[🐛 Report an Issue / 오류 제보](https://github.com/teachtv/Tournament-Bracket-Generator/issues)

---

**Developed by 티치TV (TEACH_TV)**

© 2026 TEACH_TV. All rights reserved.
