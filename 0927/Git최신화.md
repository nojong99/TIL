# Git

분산버전관리시스템 

### CLI

명령어 기본 구조 

- 컴퓨터 정보 

    ls  -al 

- 디렉토리

  cd 경로 - 경로 변경 

  ls - 목록

  mkdir - 디렉토리 생성

  touch - 파일의 날짜와 시간 수정 ( 0바이트 빈 파일 생성 )

- 저장소 생성 명령어 -init

  > git init  

1. git init ( .git이라는 숨김 폴더 생성  + cli 환경에서 master 뒤에 추가)

2. add 를 통해 commit 될 변경사항 들을 최신화시킨다. ( 단, 버전관리 시 변경사항이 있어야한다. )

   > git add .  - git 저장소 생성. (master) 브랜치 생성
   >
   > git commit -m '변경명' 
   >
   > git status  (Working directory 상태를 보여줌)
   >
   > git log  (commit 을 조회 )
   >
   > 
   >
   > <img src="C:\Users\nojon\Desktop\0927_노력의결과\git 최신화 과정.PNG" alt="git 최신화 과정" style="zoom:50%;" >
   >
   > 
   >
   > 

<span style="color:red">※ **기초 설정** => git congfig --global user.email "이메일" // git congfig --global user.name "닉네임" </span>







# 파일 라이프사이클

![image-20210927152304523](C:\Users\nojon\AppData\Roaming\Typora\typora-user-images\image-20210927152304523.png)



## 원격 저장소 관리 

> 원격 저장소를 제공하는 서비스는 다양하지만, GitHub을 사용



### 원격 저장소 등록

```
$ git remote add origin https://github.com/com/username/repository_name.git
```

> origin 이름으로 특정 url 등록



### 원격 저장소 push 

``` git push origin master
$ git push origin master
```

>  origin으로 지정된 원격 저장소의  master로 push



## 깃 리모트 변경 하기



### 기존 리포지토리 깔끔하게 pull / push

```
git pull
git add .
git commit -m "clean push"
git push
```

### 기존 리포지토리 remote 제거

```
git remote remove origin
```

### 새 리포지토리 remote 추가

```https://gist.github.com/480/4681b67d2a906db8c6c1321cc678f05f
git remote add origin https://github.com/계정/리포지토리
```





 



