# 잘못된 git 계정으로 git history가 생성되는 경우

1. `git config --list`로 현재 계정을 확인해봅니다.
    
    `user.email`이 회사 계정으로 설정되어 있는지 확인해봅니다.

2. 회사 계정이 아닌 경우, `git config --unset --global user.email`로 `user.email` 설정을 제거합니다.

3. `git config --global user.email [회사계정]`으로 새롭게 설정해줍니다.

# 참고 레퍼런스

https://webisfree.com/2018-07-26/git-config-%EC%84%A4%EC%A0%95-%ED%99%95%EC%9D%B8-%EB%B0%8F-%EB%B3%80%EA%B2%BD%ED%95%98%EA%B8%B0