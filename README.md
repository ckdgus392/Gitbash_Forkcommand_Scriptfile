# Github(프로젝트 협업) - Fork command


1. **팀장 repository 생성(create)**


1. **팀원 - 팀장 repository 복제(fork)**


1. **git bash를 통해 my repository 클론(clone) //생성폴더명은 생략가능**
    
    `$ git clone [로컬 저장소 주소] [생성 폴더명]`
    


1. **로컬 저장소에 원본(Upstream) 저장소 등록 및 연결상태 확인**
    
    `$ git remote add upstream [원격 저장소 주소]`
    
    `$ git remote -v`
    
    4-1. fetch
    
    `$ git fetch upstream`
    
    `※ fetch는 원격 저장소에 변경사항이 있는지 확인만 함.`
    
    `※ 변경된 데이터를 로컬 Git에 실제로 가져오지는 않는다.`
    

1. **stage area에 올려 놓을 파일 확인**
    
    `$ git status`
    


1. **commit할 파일 stage area에 올리기**
    
    `$ git add .` or `$ git add [파일명]`
    


1. **commit**
    
    `$ git commit -m "commit message"`
    
    **7-1. commit 확인 및 취소**
    
    `$ git log` → `$ git reset HEAD^`
    


1. **push**
    
    `$ git push origin [branch명]`
    
-----
1. **pull(최신화 하기)**

    `$ git pull origin [branch명]`
    
    `$ git fetch origin [branch명]`
---

- git bash

[[Github] 외부저장소 fork, pull request, 동기화 하기](https://velog.io/@jisubin12/Github-외부저장소-fork-pull-request-동기화-하기)

[Git 명령어 총정리집 (by 코딩알려주는 누나❤) - HackMD](https://hackmd.io/@oW_dDxdsRoSpl0M64Tfg2g/ByfwpNJ-K)

- git flow

[[Git] GitHub로 협업하기 - Forking Workflow](https://velog.io/@hyowon_lee/Git-GitHub로-협업하기-Forking-Workflow)
