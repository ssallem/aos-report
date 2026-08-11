# 앱 생성·배포 자동화 검토

Android 앱 템플릿 포트폴리오(Diem · Penna)의 **제작·배포 과정을 어디까지 자동화할 수 있는지** 조사한 보고서입니다.

**보고서 → https://ssallem.github.io/aos-report/**

## 요약

| | 자동화 가능분 |
|---|---|
| 앱 **생성**(제작) | 40단계 중 15단계 완전 자동 · 21단계 반자동 |
| 앱 **배포** — 신규 앱 첫 출시 | 10~15% (구글이 앱 등록·심사·법적 선언 관문을 API에 열지 않음) |
| 앱 **배포** — 기존 앱 업데이트 | 90~95% |

Google Play Android Developer API 공식 문서 원문 확인 기준(2026-08-11).

## 구성

- `index.html` — 보고서 본문. 외부 폰트 CDN 외 의존성 없는 단일 파일
- 테마: "Quiet Sheet" ([레퍼런스 구현](https://ssallem.github.io/penna-app/))
