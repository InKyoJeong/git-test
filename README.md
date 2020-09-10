## git test

- **Fork**
- `git clone 'https://.../git-test'`
- `cd git-test`
- `code .`

#### test branch

- `git checkout -b test-branch`
- (something change)
- `git add .`
- `git commit -m"test branch"`
- `git push origin test-branch`
- Add a Pull Request
- Review & Merge in github

#### Add Remote

- `git remote add upstream https://github.com/ingg-git/git-test`
  - 원 저장소를 'upstream'이라는 이름의 리모트로 추가
- `git fetch upstream`
  - 리모트에서 최신 데이터를 Fetch
- `git merge upstream/master`
  - 대상 브랜치를 토픽 브랜치에 Merge
- `git push`
