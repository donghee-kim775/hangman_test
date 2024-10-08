# Hangman File
| Git Hub - 실습

#### repo를 local에서 만들기
```
>> git init
```
ouput) Initialized empty Git repository in C:/Users/DCU/Desktop/ubuntu_backup/hangman_test/.git/

```
>> git log
```
ouput) fatal: your current branch 'master' does not have any commits yet

#### 변경한 파일 중 repo에 추가하고싶은 것들 선택
```
>> git add hangman.py README.md
```

#### git commit -m "변경된 message"
```
>> git commit -m "initial commit" hangman.py README.md
```
output)
[master (root-commit) 42dbf8d] initial commit
 2 files changed, 178 insertions(+)
 create mode 100644 README.md
 create mode 100644 hangman.py

#### local repo의 remote repo 위치를 지정
```
>> git remote add origin https://github.com/donghee-kim775/hangman_test.git
```

#### git branch -M : 현재 Local repo의 이름을 main으로 변경
```
>> git branch -M main
>> git branch
```

#### git push -u origin (branch name) : branch 된 변경사항 push
```
>> git push -u origin main
```