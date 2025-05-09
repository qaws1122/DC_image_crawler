# DCinside 이미지 크롤러

## 소개
디시인사이드(DCinside) 갤러리 게시물의 이미지를 자동으로 다운로드하는 크롤러입니다.

## 설치 방법
[다운로드](https://github.com/qaws1122/DC_image_crawler/releases/tag/qasw1122) Crawler.zip 다운로드

## 주요 기능 (파일명)
- 갤러리 게시물 자동 모니터링 및 신규 이미지 다운로드
- 중복 이미지 확인 (data.json)
- 다운로드된 이미지의 날짜, URL 주소, 작성자, 아이디, 아이피 수집 (Download_History.log)
- 로그 (crawler.log)

## ⚠️ 주의 사항 ⚠️
***자세한 사항은 프로그램 내부 도움말을 읽어주시기 바랍니다.***
- 비정상 종료 시 중복 체크 데이터가 손실될 수 있습니다.
- "n개의 새 게시물을 성공적으로 처리했습니다" 메시지는 데이터가 안전하게 저장되었음을 의미합니다.
- 크롤링 정책을 준수하고 과도한 요청을 자제하세요.
- 다운로드한 이미지의 저작권을 존중하고 개인 용도로만 사용하세요.
- ***너무 짧은 대기 시간은 아이피가 차단될 수 있습니다.*** (일시적)
- 기존 설정값을 유지하는 걸 권장 드립니다.
## 설정 옵션
메뉴의 [설정] → [설정 보기/수정]에서 조정 가능:

- **일반**: 파일 저장 위치, 최대 처리 개수 등
- **네트워크**: 재시도 횟수, 대기 시간, 동시 처리 수 등
- **로깅**: 로그 형식, 레벨, 파일 크기 등
- **고급**: 선택자 설정, 도메인 등
