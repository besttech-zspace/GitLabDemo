# Feature 브랜치 
- Feautre는 개발하는 기능별로 매번 새로 만들어서 사용 ex) feature-login
  - create branch : `git checkout -b new-branch-name`
- 해당 기능 개발을 완료하면, main 브랜치로 커밋, pull request
- (논의 필요) Pull Request에 대한 Review 정책
  -  Review를 할 것인지
  -  어떤 작업 사항에 한해 리뷰할 것인지 (ex. minor 수정은 리뷰 X)
  -  리뷰는 누가 할 것인지
  -> 이러한 논의를 바탕으로 Github을 통해 리뷰 정책 세팅 가능
-커밋 순서
    1. `git add file-name`  을 통해 작업한 파일 중 어떤 파일들을 커밋 할 지 선택 (모든 작업사항 반영시 git add .)
    2. git commit을 통해 add한 작업 커밋. 이 때 커밋 메시지는 팀원이 이해할 수 있도록 어떠한 작업을 했는지 적어주기. ex) `git commit -m "Refactor JavaScript code and update video thumbnail"`
    3. `git push origin main` -> 이후 충돌사항 수정 후 merge


- 추후 github actions등을 통하여 CI/CD 구축 고려 
