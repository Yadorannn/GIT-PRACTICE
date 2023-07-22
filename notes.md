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
