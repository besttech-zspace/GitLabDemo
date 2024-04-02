#main
- main 브랜치에는 각 feautre 브랜치에서 작업한 코드들이 merge됨
  - merge 과정에서 코드 리뷰 & 충돌 수정 작업이 진행됨
  - 브랜치 이동 : git checkout branch-name
  - 개발 중 오류사항이 있으면 여기에서 테스팅 -> feature에서 작업 후 다시 main으로 merge
- 테스팅 후 문제가 없으면 소스 코드를 production으로 commit & push
- 핫픽스가 필요한 경우, main-hotfix 브랜치 개설 후 테스팅
