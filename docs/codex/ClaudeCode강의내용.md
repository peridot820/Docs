# 새 문서
박영웅 강사님 강의

홈페이지 : HEROPY.DEV | HEROPY.DEV

## SKills란?

: 반복적으로 Prompt입력하는 내용을 미리 저장해두고 / 슬래쉬로 호출해서 사용하는 기능

: PR이나, 커밋푸쉬나 그런거에 활용 가능할듯 

: 플러그인중에 skill-creator가있음 그걸로 내가 대충만든 skill을 개선해달라고하거나 신규생성하면됨

:프롬프트 입력창에서 줄바꿈은 백슬래쉬\ 엔터나 alt+엔터

prd폴더에 요구사항을 md파일로 넣어서 프롬프트 내용을 입력해둔다.

## find-skill 등록하기 (skill 찾기 기능)

기존에 사람들이 만들어둔 skills The Agent Skills Directory 등록되어있음.

이중에 인기순위 조회해보면 skills 찾기 skills가 1위임 :  find-skills 

https://skills.sh 사이트에서 스킬을 검색하거나, 혹은 다음과 같이 find-skills 스킬을 설치하고 클로드에서 자연어로 검색할 수 있습니다.

```bash
# find-skills 설치
npx skills add https://github.com/vercel-labs/skills --skill find-skills

# Claude Code 프롬프트에서 사용
❯ /find-skills 프론트엔드에서 예쁘게 디자인을 하는 스킬을 추천해 줘.
```

## ByPassPermission설정해두기

.claude 폴더하위에 settings.json파일 만들고

```json
{
    "permissions": {
        "defaultMode": "bypassPermissions"
    }
}
```
