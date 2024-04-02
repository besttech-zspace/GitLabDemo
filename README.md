#main
- main 브랜치에는 각 feautre 브랜치에서 작업한 코드들이 merge됨
  - merge 과정에서 코드 리뷰 & 충돌 수정 작업이 진행됨
  - 브랜치 이동 : `git checkout branch-name`
  - 개발 중 오류사항이 있으면 여기에서 테스팅 -> feature에서 작업 후 다시 main으로 merge
- feature 브랜치에서 작업시, main 브랜치의 코드를 기준으로 최신화 시키면 됨
  - `git pull origin main`, `git fetch origin main`
- 테스팅 후 문제가 없으면 소스 코드를 production으로 commit & push
- 핫픽스가 필요한 경우, main-hotfix 브랜치 개설 후 테스팅

  
* 특이사항
  - 각자의 branch에서 동일한 부분을 작업한 경우
  - A가 작업하고 커밋 후, B도 작업하고 커밋. 그러나 A의 작업사항에 문제가 있어 이를 롤백해야 하는 경우
