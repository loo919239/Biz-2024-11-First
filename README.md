# 나의 첫 프로젝트
- Repository 정보 등록
- 원격 Repository 생성
- 로컬 폴터(test1)에
README.md 파일 생성
- 로컬 Repository 생성
- 로컬 폴더 압축하여 로컬 Repository에 저장
- Repository에 push하기


## Repository 정보 등록
-컴퓨터를 포멧했을 때 최초 한번만
- username 등록: **git config -- global user.name loo919239**
-email 등록 : **git config -- global user.email loo919239@loo919239.com**

## 로컬 Repository 생성하기
- **bash shell**에서 **bit init** 명령 실행하기: **.git** 폴터가 생성된다.
## 원격 Repository 와 로컬 Repository 연결하기 :  git remote add origin https://github.com/loo919239/Biz-2024-11-First.git

## 원격 Repository에 push하기
- 로컬 폴터의 파일, 폴더 들을 로컬 Repository에 압축하여 저장하기 : ** git add README.md
- 왜 push를 하는지 comment 부착하기 : **git commit -m"커멘트"**
- push하