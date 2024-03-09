#Study Site

#<span style="color:red">**개인 token 생성방법**</span>

1.참조사이트 : 

<https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens>

#<span style="color:red">**Git & Github 명령어**</span>


##<span style="color:blue">**Git Bash 명령어**</span>

    pwd : 현재 폴더 디렉토리
    ls : 현재폴더 파일리스트
    ls -al : 숨긴폴더까지 확인
    cd : 폴더 변경
    cd - : 이전 폴더로 돌아가기

##<span style="color:blue">**GitHub에 코드를 올리는 과정**</span>

    git init : 내 프로젝트에 git 사용git add [파일명] : 원하는 파일만 선택
    git add . : 전체파일 선택
    git commit -m “메세지 코멘트” : 메세지를 달아 커밋으로 만들기
    git log : 생성한 커밋 보기
    git log 나가기 : 키보드 Q키
    git remote add : GitHub 저장소 주소 알려주기
    (git remote add [원격저장소이름] [원격저장소 주소])
    git remote add origin https://github.com/sewoong2023/study2024.git
    git push : GitHub에 올리기
    (Git push [원격저장소 이름] [브렌치명(default: master)])
    git push -u origin main

##<span style="color:blue">**기타**</span>
    
    git show-ref : 브랜치명 확인
    git branch -m master main : breach명 변경 (master -> main)
    token : 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
    