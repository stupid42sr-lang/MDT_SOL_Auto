# MDT SOL Auto

SOL Auto **업데이트 배포 전용** Public 저장소입니다.

개발 소스코드는 이 저장소에 올리지 않습니다.  
실제 개발은 Macro Developer Tool 저장소에서 별도로 관리합니다.

## 이 저장소에 허용되는 것

- `README.md`
- GitHub **Release** 배포 파일만

### Release 에셋 (자동업데이트용)

- `MDT_SOL_Auto_Update.zip`
- `SHA256SUMS`
- (ZIP 내부에 `SOL_Auto.exe`, `updater.exe` 등 기존 배포 구성 포함)

## 이 저장소에 올리면 안 되는 것

- Python / 개발 소스코드
- `core/`, `runtime/`, `scripts/` 등 개발 트리
- `license.dat`
- 사용자 `data/` (설정·로그·개인 데이터)

## 자동업데이트

클라이언트는 이 저장소의 **최신 Release** 를 조회합니다.  
기존 자동업데이트 구조(공개 Release + ZIP + SHA256SUMS)를 유지합니다.
