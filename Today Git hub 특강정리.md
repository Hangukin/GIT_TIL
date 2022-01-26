# 1.25 특강 

## 배쉬 명령어

1. **date**  - 현재 시간 알려줌 

   

2. **~**  : 루트 , 홈 디렉토리

   

3. **ls ( list segments )**  : 현재 경로내의 폴더와 파일 목록 나열 
   **ls - a**  : 숨김폴더 파일까지 확인 

   
   
4. **ctrl + l ** : 스크롤 내려 화면 정리 
   **clear ** 화면창 삭제 깨긋하게 정리
   
   

5. **배쉬창 화살표 키**  => 최근 기입확인

 

6. **ctrl + a or  e**  => 앞 뒤 이동 

   

7. **touch 파일명.확장자**  => ' 파일 만드는 경우 '

     

8. **mkdir ( make directory )** => 현재 경로 폴더 생성

     

9. **cd (change directory) **=> 경로 변경 
    **. **=> 현재위치

  **.. **=> 현재 위치에서 상대 경로 상위 

  

10. **mv** : 경로명, 파일명 변경

     

10.  **rm** => remove
     **rm a.txt** 파일 삭제
     **rm -r test**  폴더삭제
        
    **rm **.txt 텍스트삭제 전부 삭제 (**최대한 안쓰기!!**)
    
    **rm -rf ** 숨김파일까지 강제 삭제 (**최대한 안쓰기!!**) 

## 깃 명령어

1. **git init **
-> 현재 폴더를 깃이 관리하는 폴더로 만듦
** 홈 폴더에서 기입 x ** 
**딱 최초 1회만 기입!** 

2. **git status** 
  => 현 상황을 보고싶을때 

   `Untracked` : Git이 관리하지 않는 파일 (한번도 Staging Area에 올라간 적 없는 파일)

  ```
  Tracked
  ```

   : Git이 관리하는 파일

  ​     a.  `Unmodified` : 최신 상태

  ​     b.  `Modified` : 수정되었지만 아직 Staging Area에는 반영하지 않은 상태

  ​     c.  `Staged` : Staging Area에 올라간 상태

3. **git add a.txt**
전부 다 올리기

4. **git commit -m "메시지"** 
-> 메시지 저장소 
컨벤션 (convention)
numpy/bugfix/

5. **git log**
=> 버전들 확인할래! 

6.   **git config --global user.email " 이메일 "** 
     **git config --global user.name " 이름 "**

7. **git config --global --list 리스트** 

   위 이메일 이름 리스트 보여줌.

## 타이포라 문법 

'#'

문서 논리적 흐름 대제목 소제목 주의 글씨 크기 키우기위해 사용은 x



1. **'>'**인용문
2.   **'*'**순서없는 목록
3. 1. 순서있는 목록
    [ Tab => 안으로 간다
     [ shift + tab => 밖으로 나옴 

4. **'```' **코드블럭 생성 

   **Inline**

   - 인라인 블럭으로 처리하고 싶은 부분을 **`** (백틱) 으로 감싸줍니다.

   **Block**

   - **`** (백틱) 을 3번 입력하고 `Enter` 를 눌러 생성합니다.

`add` 한 요소를 remote 저장소에 올리려면 `$ git push origin master` 를 터미널에 입력합니다.

5. **이미지 생성 **

- `![]()` 을 작성하고 `()` 안에 이미지 주소를 입력합니다. `[]` 안에는 이미지 파일의 이름을 작성합니다.
- 로컬에 이미파일을 저장한 경우 절대 경로가 아닌 상대 경로를 사용하여 이미지를 저장합니다.

![git-github-image](https://miro.medium.com/max/3586/1*mtsk3fQ_BRemFidhkel3dA.png)

6. **링크 설정 **

   대괄호 안에 실제링크제목  소괄호에 주소 

`[]()` 을 작성하고 `()` 안에 링크 주소를 작성하고 `[]` 안에 어떤 링크 주소인지 작성합니다.

[git 공식문서](https://git-scm.com/)

[github 공식문서](https://github.com/)

## 타이포라 단축기

1. ctrl + T 표만들기 

# 1.26 특강

