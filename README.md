
# 글로벌 계정 설정 
```
git config --global user.name "your-name"
git config --global user.email "your@email.com"
```

# 저장소별 계정 설정 
```
git config --local user.name "your-name"
git config --local user.email "your@email.com"
```

# remote
- 로컬 저장소와 원격 저장소 연동 명령어 
- git remote add [name] [remote-repository-address]
- ![remote](./images/remote.png)
- `git remote add origin https://github.com/LEEHANI/git-practice.git`
- 보통은 나의 repository를 origin으로 놓고 사용함. 
- `git remote` or `git remote -v`로 연결 상태 확인 가능
