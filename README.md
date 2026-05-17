# KChatMacro

> Windows용 K사 채팅 매크로 — 다중 세션 / 변수 치환 / 스케줄 발송 / 트레이 상주.

[ReWorld](https://reworld.kr) 데스크톱 앱의 **release 배포 채널**입니다. 소스 코드는 별도 모노레포(`reworld-kr/ReWorld`)에서 관리되고, 이 repo는 빌드 산출물(`KChatMacro.exe`, NSIS installer, checksums)만 호스팅합니다.

## 다운로드

[**최신 버전 다운로드 ↓**](https://github.com/reworld-kr/KChatMacro/releases/latest)

- `KChatMacro.exe` — bare 실행 파일 (압축/설치 없이 즉시 실행)
- `KChatMacro_Setup.exe` — NSIS 설치 마법사 (사용자 디렉터리에 설치, UAC 불필요)
- `checksums.txt` — SHA-256 무결성 검증

설치 후 자동 업데이트가 켜져 있어 새 버전 출시 시 다음 실행에 백그라운드 적용됩니다.

## 주요 기능

- Windows SendInput 기반 안정적 입력
- 여러 채팅방 세션 동시 관리 + 트레이 상주
- 변수 / 플레이스홀더 자동 치환 (random / sequential / static)
- 그룹 단위 송신 간격 + 세션 단위 loop 간격
- 시간대 활성 윈도우 (예: 09:00–18:00 에만 발송)
- 워크스페이스 자동 저장 + JSON 임의 경로 import/export

## 시스템 요구사항

- Windows 10 / 11 (x64)
- 사용자 디렉터리 설치 → 관리자 권한 / UAC 불필요
- 자동 업데이트 — GitHub Release 채널 모니터링

## 라이선스

- **첫 실행 시 3일 무료 체험** 자동 발급
- 정식 라이선스는 [reworld.kr/pricing](https://reworld.kr/pricing) 에서 구매
- 라이선스 관리 / 본인 라이선스 조회: [reworld.kr/account](https://reworld.kr/account)

데스크톱 + 모바일 + HomePage 모두 **동일 ReWorld 계정**을 공유합니다. 한 번 로그인하면 보유한 라이선스가 모든 플랫폼에 동일 적용됩니다.

## 문의 / 버그 리포트

- 일반 문의: [reworld.kr/contact](https://reworld.kr/contact)
- 버그 / 기능 요청: [Issues](https://github.com/reworld-kr/KChatMacro/issues)

## 관련 링크

- [KChatMacro 제품 페이지](https://reworld.kr/apps/kchatmacro)
- [ReWorld 앱 그리드](https://reworld.kr/apps)
- [이용약관](https://reworld.kr/legal/terms) / [개인정보처리방침](https://reworld.kr/legal/privacy)
