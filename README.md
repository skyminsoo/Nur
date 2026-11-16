# 누르 온라인 — 테스트 버전

정적 사이트입니다. 빌드 과정 없이 index.html 하나로 동작합니다.

## Vercel 배포
1. GitHub에 새 저장소를 만들고 이 폴더의 파일을 그대로 올립니다.
2. Vercel > Add New > Project 에서 해당 저장소를 Import 합니다.
3. Framework Preset: Other, Build Command / Output Directory: 비워 둠 > Deploy.

## 낭송 음원 넣기 (선택)
1. 사용권을 확보한 음원 파일을 audio/fatiha.mp3 로 넣습니다.
2. index.html 의 CONFIG 에서 RECITATION_URL:'' 을 RECITATION_URL:'audio/fatiha.mp3' 로 바꿉니다.
   (1시간 동안 반복 재생됩니다. 비워 두면 잔잔한 배경음이 나옵니다.)

## 현재 상태
- 결제: 테스트 모드 (실제 청구 없음). index.html 의 "실결제 연동 지점" 주석 위치에 결제대행사 연동 필요.
- 저장: 브라우저 localStorage (기기별 저장, 서버 계정 없음).
- 다른 순례자: 자동 캐릭터 (실시간 멀티플레이 없음).
