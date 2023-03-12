# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성
# git 배운 내용 정리 #

## git이란 ##

파일을 관리하기 편하게 해주는 분산형 버전 관리 시스템
***
**로컬 저장소 만들기**
1. 만드려는 폴더 위치에서 마우스 우클릭 후 Git Bash Here 클릭
2. git init 입력
3. git 폴더가 생기면 저장소 생성 성공.
***
**정보 등록하는 법**
1. git config --global user.name "ㅁㅁㅁ" 
2. git config --global user.email "ㅁㅁㅁ@ㅁㅁ.com" 
(github에서 사용하려면 이름과 이메일을 github와 똑같이 설정해야 합니다.)
***
   
**주로 사용한 Bash 명령어**
   
cd ㅁ: ㅁ 폴더로 이동   
cd .. : 현재 폴더에서 바로 상위 폴더로 이동   
cd - : 바로 이전 폴더로 이동   
pwd : 현재 디렉토리 위치를 확인   
clear : 현재 콘솔창에 입력,출력 내용을 화면에서 지움   
touch ㅁ : ㅁ 파일을 생성   
mkdir ㅁ : ㅁ 폴더를 생성   
***
**사용한 git 명령어**   
   
git add README.md : 파일 추가할 때 기본으로 사용   
git add . : 추가할 파일이 여러개인 경우, 사용   
git commit -m "ㅁ" : 메시지 작성    
**(commit 하기 전, add을 먼저 입력해야합니다.)**   
git commit -am "ㅁ" : 두번째 commit 부터는 am 명령어로 add과 commit을 같이 입력 가능   
git status : 현재 상태를 확인   
git log : 모든 commit 이력을 확인   
git log --oneline : 간략하게 commit 이력을 확인   
git log --graph : commit 이력을 그래프로 표시   
git log --all : 다른 branch의 commit 이력도 확인 가능   
git branch ㅁ : ㅁ 브랜치를 생성   
git switch ㅁ : ㅁ 브랜치로 이동   
git branch -d ㅁ : ㅁ 브랜치를 이미 푸쉬하고 병합 되었을 경우에만 삭제   
git branch -D ㅁ : ㅁ 브랜치를 강제 삭제   
git branch --list 와 git branch -a : 브랜치 리스트를 확인   
git merge ㅁ : 현재 브랜치에서 ㅁ 브랜치를 합침   
git rm ㅁ : ㅁ 파일을 삭제   
git rm -r ㅁ : ㅁ 디렉토리를 삭제 **(파일이 있는 경우 삭제되지 않음.)**   
git -rf ㅁ : ㅁ 디렉토리에 파일이 있어도 강제 삭제   
git commit --amend -m "ㅁ" : 바로 직전의 커밋 메시지를 수정   
git push -u origin main : main 브런치에 push   
git clone : github에서 내 저장소로 복사   
git clone  .  : 내 저장소에 미리 폴더를 만들고 복사하는 경우 사용   

