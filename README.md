# rAthena Korean Monster DB

rAthena에서 한국어 몬스터 이름을 사용할 수 있도록 만든 커스텀 몬스터 DB입니다.

## 포함 내용

- `db/import/mob_db.yml`
- 한국어 몬스터 이름 2,675개
- `Name`과 `JapaneseName`에 한국어 이름 등록
- rAthena 원본 `db/re/mob_db.yml`은 수정하지 않습니다.

## 설치

저장소의 `db/import/mob_db.yml` 파일을 rAthena 서버의 동일한 경로에 넣습니다.

```text
db/import/mob_db.yml
```

## 한국 클라이언트 사용 시

이 저장소는 몬스터 이름 DB만 제공합니다.
한국 클라이언트에서 UTF-8 한글 몬스터명이 깨지는 경우 UTF-8 → CP949 변환 소스 패치가 필요합니다.

관련 패치 저장소: `wonsangm/rathena-korean-character-patch`

## 맵 스폰 몬스터 이름

맵 스크립트에서 몬스터 이름을 영어로 직접 지정한 경우 DB의 한국어 이름이 사용되지 않을 수 있습니다.
이 경우 `--ja--` 전 맵 패치를 사용할 수 있습니다.

맵 패치 저장소: `wonsangm/rthena-korean-map-ja-patch`

## 확인 환경

- rAthena Renewal
- 한국 클라이언트 PACKETVER `20260219`
- 한국어 몬스터 DB 2,675개 로딩 확인
