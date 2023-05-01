# github_connect


##💐 1. 깃설치 🐠 (http://git-scm.com.download/win)

    git을 통해서 github와 연결할 수 있다.
    
![image](https://user-images.githubusercontent.com/129706758/235424480-723c221d-9e59-4ea5-99e0-891296b35f5b.png)


-깃에 올려야 할 폴더에 shift + 우클릭하여 PowerShell 창열기


    열린창에 git init 작성하면,
    
- .git 폴더가 생성됨

------------------------------------------------------------

##💐 2. 깃설치 후 Git bash 열기 🐠

![image](https://user-images.githubusercontent.com/129706758/235417846-8085469b-44e8-4b55-a01f-a7ea15741740.png)

* 유저 이름 설정하기

            git config --global user.name "lee yena"

* 유저 이메일 설정하기 (반드시 github에 가입했던 이메일 주소와 동일해야 한다.)

            git config --global user.email "leeyena4724@naver.com"

* 내 정보 확인하기

            git config --list
            


## 위 연결은 해당 컴퓨터에서 한번만 실행하면 됨
----------------------------------------------------


# github에 코드 업로드하기

        * 초기화
            git init
        * 추가할 파일(폴더안의 내용을 모두 올림)
            git add .
        * 히스토리 만들기 (-m 은 메시지를 의미함 ""안에는 히스토리 이름을 작성)
            git commit -m "first commit(한글도 가능)"
        * Github의 repository를 만들고 그 곳에 만든 주소를 넣는다
            git remote add origin https://github.com/YENAZIGMINA/cssGit_flex.git
        * 연결이 잘 되었는지 확인하기 (사용안해도 됨)
            git remote -v
            
