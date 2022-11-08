# Git 회사 계정과 개인 계정 따로 사용하기

https://www.lainyzine.com/ko/article/useful-git-settings-when-using-github-multi-account/

이 링크를 참고해서 나름 따라했는데 git init 하는 경우 밖에 안나와있어서 잘 되는지 테스트 해보려고 합니다.

해보니 커밋시 기본 신원 정보가 없다고 나옵니다.

즉 글로벌 유저가 설정이 안되어있을 때 커밋을 못하는 것은 설정이 되었는데, 폴더별 .gitconfig는 설정이 되지 못했다는 것..!

https://kir93.tistory.com/entry/%ED%8F%B4%EB%8D%94-%EB%B3%84-%EB%8B%A4%EB%A5%B8-Github-%EA%B3%84%EC%A0%95-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0

이 링크를 참고해서 디렉토리 별로 config를 두지 않고, ~위치에 넣어보았습니다.

여전히 안되고 있습니다..

아 그런 문제들이 아니라 config 파일에서 \[user\] 안에 또 user.name으로 설정해서 인식을 못했던 것이었습니다. 해결!