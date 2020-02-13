KaKao Clone 이론 정리
======================
# 1일차 정리
---------------------------------------
## 1. Git
### 1.1. 구성
    1. repository : 내 파일을 저장하는 폴더
    2. commit : 파일의 변경사항을 기록함, 저장
    3. branch : 나무의 가지, default는 master, 다른 가지의 브랜치를 만들 수 있고 관리할 수 있음,
### 1.2. branch 사용법
    1. 브랜치 만들기
    2. 마스터는 그대로 둔다.
    3. 브랜치에서 새로운 작업 후 작업이 완료하면,
    4. 브랜치를 마스터에 결합시킨다.
### 1.3. Git과 Github의 차이점
    1. Git : 코드의 변경사항을 추적하는 시스템, 코드가 언제, 어떻게 누구에 의해 변경 되었는지
    2. Github : 인터넷 저장소, 변경사항을 저장하는 클라우드
---------------------------------------
## 2. HTML    
### 2.1. Html Semantic Tags OR Non Semantic Tags
    1. Semantic Tags : 의미가 있는 태그
        1. <h1> : 헤더 1이라는 의미
        2. <header, article, footer>
    2. Non Semantic Tags : 아무 의미가 없는 태그
        1. <div> : 아무 의미가 없음, 컨테이너 박스
        2. <span> : 텍스트를 위한 박스
### 2.2. Tag안의 id와 class
    1. Id : id값은 오직 한가지의 값만 가질 수 있다, 반복하지 않는 태그를 정의할 때 사용
    2. Class : 여러 태그에서 같은 class를 가질 수 있다, 반복되는 내용을 사용할 때 사용
---------------------------------------    
## 3. CSS 
### 3.1. Element의 Box Model
    1. 컨텐츠(contents) : 실제 내용
    2. 보더(border) : 박스의 경계
        - Border의 다양한 style 주는 법
            1. Border-width : 보더의 폭 > border-width : 5px
            2. Border-color : 보더의 색상 > border-color : red
            3. Border-style : 보더의 스타일 > border-style : solid(실선)
            4. 위의 세개를 한번에 > border : 5px(폭) solid(스타일) red(색상)
    3. 패딩(padding) : 박스의 보더에서 안쪽으로 있는 간격
    4. 마진(margin) : 박스의 보더에서 바깥쪽으로 있는 간격
        - Padding, margin 여러 방법으로 주는 법
            1. 전체 > padding : 20px
            2. 상하,좌우 > padding : 20px(상하) 10px(좌우)
            3. 상우하좌 > padding : 20px(상) 10px(우) 5px(하) 2px(좌)
### 3.2. Css의 Selector의 종류
    1. Tag name : ex) h1, span, div
    2. Id : 사용법 > #id_name
    3. Class : 사용법 > .class_name
### 3.3. HTML 파일과 CSS 연결 방법
    1. Inline : HTML 파일 안에 <style>태그를 사용해 css를 주는 방법
        - 단점 : 같은 css를 사용하더라도 모든 html 문서에 작업을 해주어야 함, 비효율적
    2. Link : <link> 태그를 사용하여 html파일에 css파일을 적용 시켜 줌
        - 장점 : 여러 html 파일을 하나의 css 파일로 관리할 수 있음

