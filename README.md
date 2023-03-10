# 뚜셰(Touché) 관리자 (macOS)

<p align=center>
    <img src="img/readme.png">
</p>


## 프로젝트 소개 


> `향수`에 대해 관심을 갖기 시작해, 다양한 `향수` 정보를 얻고 싶은 사람을 위한
> 기본적인 `향수` 정보, 시각화 정보를 제공해 `향수` 정보를 보다 직관적으로 알 수 있도록 돕는 `뚜셰(Touché) 관리자` 입니다.


## 멋쟁이 사자처럼 App School 1기 Final Project 대상 수상

<p align=center>
    <img style="border: 1px solid black;" src="./img/Touche.png" width=50%>
</p>


## Skills & Tech Stack

<p>
  <h4>개발</h4>
    <span>
      <img src="https://img.shields.io/badge/macOS%2013.0+-FF6000?style=flat-square&logoColor=white"/>
      <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white"/>
      <img src="https://img.shields.io/badge/SwiftUI-0061b7?style=flat-square&logo=swift&logoColor=white"/>
      <img src="https://img.shields.io/badge/Xcode 14.2-147EFB?style=flat-square&logo=xcode&logoColor=white"/>
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=Firebase&logoColor=orange"/>
    </span>
  <br/>
  <h4>협업 / 디자인</h4>
    <span>
      <img src="https://img.shields.io/badge/Github-000000?style=flat-square&logo=github&logoColor=white"/>
      <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=Jira&logoColor=white"/>
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/>
    </span>
    
</p>


## 컨벤션


```
- [Feat] : 새로운 기능 추가
- [Add]: 새로운 파일 추가 (json, img, asset, 목업데이터 등등)
- [Fix] : 버그 수정
- [Docs] : 문서 수정
- [Style] : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- [Refactor] : 코드 리펙토링
- [Test] : 테스트 코드, 리펙토링 테스트 코드 추가
- [Chore] : 빌드 업무 수정, 패키지 매니저 수정
```


## 🎁 Library


| Name              | Version |       |
| ----------------- | :-----: | ----- |
| Firebase          | `9.0.0` | `SPM` |
| SwiftSoup         | `2.5.3` | `SPM` |


## 주요기능과 스크린샷


<table border>
    <tr>
        <td><img src="img/6.png"></td>
    </tr>
    <tr>
        <td><p align=center>로그인 뷰</p></td>
    </tr>
    <tr>
        <td><img src="img/3.png"></td>
        <td><img src="img/4.png"></td>
        <td><img src="img/5.png"></td>
    </tr>
    <tr>
        <td><p align=center>메거진 등록 - 향수 선택 뷰</p></td>
        <td><p align=center>메거진 등록 - 메거진 수정/저장 뷰</p></td>
        <td><p align=center>메거진 뷰</p></td>
    </tr>
    <tr>
        <td><img src="img/1.png"></td>
        <td><img src="img/2.png"></td>
    </tr>
    <tr>
        <td><p align=center>데이터 로그 확인 뷰</p></td>
        <td><p align=center>데이터 업로드 뷰</p></td>
    </tr>
</table>


## 프로젝트 정보

1. 최초 로그인을 실행한다.
2. 메거진탭을 선택해서 원하는 작업을 실행한다.
    - `+ 버튼`을 눌러 메거진 데이터를 생성한다.
    - `trash 버튼`을 눌러 메거진 데이터를 삭제한다.
    - `edit 버튼`을 눌러 메거진 데이터를 수정한다.
3. 서버탭을 선택해서 네트워크를 선택해 향수데이터를 서버에 저장한다.
    - `제품 불러오기`를 눌러 60개 향수 제품을 불러온다.
    - 향수 제품을 클릭해서 하나씩 서버에 저장한다.
    - 모두 저장하기 버튼을 눌러 전부 저장한다.
4. 서버탭을 선택해서 로그를 선택해 향수데이터 및 메거진데이터의 서버와 디바이스 통신 로그를  확인할 수 있다.


## 데모영상

<img src="img/touche.gif">

## 개발자


| <img src="https://avatars.githubusercontent.com/u/68586179?v=4" width=200> |
| :------------------------------------------------------------------------: |
|                   광현</br>[@seo-kh](https://github.com/seo-kh)<br/>        |


## 앱 설치 실행 가이드

elinholic95@icloud.com 으로 연락 주시면 아래 파일을 전달받으실 수 있습니다.
`GoogleService-Info.plist`

> `TocheAdmin/Store/APIStore.swift`를 사용하려면, [Sephora API](https://rapidapi.com/apidojo/api/sephora)사이트에서 계정을 생성해서 `X-RapidAPI-Key` 를 발급받아 사용하셔야 합니다. 

> 위 파일 없이 간단한 앱 빌드만 필요하시다면, 번들 아이디 com.codelion.ToucheFinal 을 입력해주세요.

## 라이센스

[MIT](https://choosealicense.com/licenses/mit/)
Touché is available under the MIT license. See the [LICENSE](https://github.com/APPSCHOOL1-REPO/finalproject-touche/blob/main/License) file for more info.

## 연관 링크

뚜셰소비자앱 레포지터리 : [https://github.com/APPSCHOOL1-REPO/finalproject-touche](https://github.com/APPSCHOOL1-REPO/finalproject-touche)
