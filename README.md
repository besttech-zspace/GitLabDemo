# Feature 브랜치 
- Feautre는 개발하는 기능별로 매번 새로 만들어서 사용 ex) feature-login
  - create branch : git checkout -b new-branch-name   
- 해당 기능 개발을 완료하면, main 브랜치로 커밋, pull request
- (논의 필요) Pull Request에 대한 Review 정책
  -  Review를 할 것인지
  -  어떤 작업 사항에 한해 리뷰할 것인지 (ex. minor 수정은 리뷰 X)
  -  리뷰는 누가 할 것인지
  -> 이러한 논의를 바탕으로 Github을 통해 리뷰 정책 세팅 가능

- 추후 github actions등을 통하여 CI/CD 구축 고려 
