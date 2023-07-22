1. 최초 설정

git config --global user.name
git config --global user.email
git config 로 확인 가능
> 프로젝트별로 나의 이름과 이메일을 남길 수 있음.

git config --global init.defaultBranch main
> master 가 아닌 main 을 사용하는 추세라고 함.

ssh-keygen / ssh 세팅 필수 

2. 폴더 진입 이후

    1. git init 
    > command shift . 으로 숨긴 파일 확인 가능 (.git 파일)
    > 기본 설정

    2. git status
    > 현재 폴더의 상황을 보여줌

    3. .gitignore
    > git에 저장하지 않는 파일 목록을 작성
    > 내용 변경시에도 변화가 없음
    
    4. git add
    > git add 특명 파일명 / git add . (전체파일)

    5. git commit 
    > git commit 하면 vim 에서 작성 가능
    > git commit -m "FIRST COMMIT!" 으로 한번에 하자
    > 근데 쉘에서 ! 와 " 을 같이 쓰면 dquote 발생 . ! 는 ' 와 같이 쓰자
    
    6. 내용 변경 후 
    > git stauts / git diff 를 통해 확인할 수 있다 

    7. Reset 과 Revert
    > Reset : 히스토리에서 삭제 : 협업 시 잘 사용 안할거 같음 
    > Revert : 히스토리에 냅두고 거꾸로 한단계 수행

    8. 과거로 돌아가기 
    > git log 에서 hash 를 가져와서
    > git reset --(옵션) 해쉬 (해쉬가 없다면 마지막 커밋을 가르킨다)
    > gir revert 해쉬 (충돌 가능성 확인)
    
    9. 브랜치 추가하기
    > git branch 브랜치명 (생성)
    > git branch (확인)
    > git switch 브랜치명 (바꾸기) / -c 브랜치명 (생성과 이동)
    > git branch -d 브랜치명 (삭제)
    > git branch -m 브랜치명 새 브랜치명 (변경)
 