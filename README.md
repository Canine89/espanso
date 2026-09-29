# espanso 설정

PC에서 사용하는 espanso 설정 백업입니다.

- `config/default.yml`: 전역 설정
- `match/base.yml`: 단축어와 치환 규칙
- 루트의 `default.yml`: 기존 저장소 경로를 유지하기 위한 `match/base.yml` 사본

복원할 때는 `espanso path`에 표시되는 Config 경로에 `config/`와 `match/` 폴더를 복사합니다. 루트의 `default.yml`은 추가로 복사하지 않습니다.

`.DS_Store`와 `.bak` 백업 파일은 제외합니다.
