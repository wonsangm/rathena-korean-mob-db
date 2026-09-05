# rAthena Korean Monster DB

rAthena 서버에서 한국어 몬스터 이름을 사용할 수 있도록 만든 커스텀 몬스터 DB입니다.

## 구성

- `db/import/mob_db.yml`
- 한국어 몬스터 이름 2,675개
- `Name`과 `JapaneseName`에 한국어 이름을 등록
- rAthena 원본 DB는 수정하지 않습니다.

## 참고

맵 스폰 스크립트에 영문 몬스터 이름이 직접 지정된 경우에는
별도의 `--ja--` 맵 패치가 필요할 수 있습니다.

전 맵 `--ja--` 패치 저장소:
`wonsangm/rthena-korean-map-ja-patch`
