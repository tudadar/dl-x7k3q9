# 대항해시대: 전설 한글패치 (배포)

《大航海時代：傳說》(대만 서비스) PC / Android(BlueStacks 포함)용 자체 제작 한글패치 배포 저장소입니다.
설치 방법·주의사항은 zip 안의 README.txt 와 https://dholegend.net/guide/kopatch 를 참고하세요.

- 번역: 자체 제작 (Claude API 번역 + 검수)
- 폰트: Noto Sans CJK KR (SIL Open Font License)
- 게임 실행 파일을 건드리지 않고, 게임이 읽는 update 폴더의 번들 3개만 교체합니다. 원본 백업·복원 기능 포함.

> **🚫 재배포 금지** — zip 파일을 다른 곳에 올리거나 재가공해 배포하지 마세요. 공유할 때는 파일 대신 안내 페이지 주소를 알려주세요: https://dholegend.net/guide/kopatch

## 설치 순서 (요약)
**PC**: ① [공식 홈페이지](https://gvl.wasabii.com.tw/install/pc_equipment.shtml) 클라이언트 설치 → 게임 실행·로그인·리소스 다운로드 완료 후 완전 종료 → ② `GVL_KoPatch_PC.zip` 풀기 → `한글패치_설치.bat` 실행(Windows 경고 시 추가 정보 → 실행) → 메뉴 1(설치) → 게임 실행.

**안드로이드 폰** (⚠ 구글 플레이 스토어 버전에는 적용되지 않음 — 공식 홈페이지 APK 필요): ① [공식 홈페이지](https://gvl.wasabii.com.tw/install/pc_equipment.shtml) APK 설치 → 게임 실행·로그인·리소스 다운로드 완료 후 완전 종료 → ② 개발자 옵션에서 USB 디버깅 ON → ③ 데이터 케이블로 PC 연결(파일 전송 모드) → `GVL_KoPatch_Android.zip` 풀고 `한글패치_설치.bat` → 폰의 'USB 디버깅 허용' 승인 → 메뉴 1(설치).

**BlueStacks**: APK 설치·실행·리소스 다운로드 후 종료 → 설정 > 고급 > ADB 켜기 → `한글패치_설치.bat` → 메뉴 1.

자세한 설명·문제 해결: https://dholegend.net/guide/kopatch

최신 다운로드: [Releases](../../releases/latest)

## 안드로이드 설치 앱 (테스트 버전)
PC·케이블 없이 폰에서 앱으로 설치/제거하는 방법입니다. 안 되면 아래 ADB 방식으로 설치하세요.
- 다운로드: https://dholegend.net/dl/apk  (릴리즈의 GVL_KoPatch_Installer.apk)
- 앱은 릴리즈의 GVL_KoPatch_AndroidData.zip(약 80MB)을 내려받아 update 폴더에 넣고 검증표를 맞춥니다.
- 안드로이드 10 이하·BlueStacks: 저장소 권한만 / 11~12: 앱에서 update 폴더 선택 / 13 이상: Shizuku(무선 디버깅) 필요
- 11~12에서 `Android/data`가 막히면: 파일 앱(내 파일 등)이 아니라 **앱의 [접근 권한 설정]으로 뜨는 폴더 선택 창**에서 골라야 합니다. 그 창에서도 막히면(삼성 갤럭시 흔함) 설정 → 애플리케이션 → 내 파일 → ⋮ → 업데이트 제거 후 재시도, 또는 Shizuku 방법을 12에서도 그대로 쓰면 됩니다.
- 앱으로 설치한 패치는 앱으로 제거하세요(PC 설치기와 백업 위치가 다릅니다).
