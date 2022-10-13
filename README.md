# GBTS_APP (로지톡)

## 1. 개요
로지톡은 수출입 화주기업과 물류기업 담당자간에 전화번호등 개인정보 교환이 없이도 대화가 가능한 수출입물류에 특화된 비지니스 메신저 서비스입니다.  
화주기업은 로지톡을 통해 손쉽게 물류기업을 검색하고 문의할 수 있으며, 물류기업은 새로운 화주기업을 만날 수 있는 기회가 있습니다.

## 2. 개발환경
- 언어 : Javascript, PHP, Swift, JAVA
- 프레임워크 : React Native
- 빌드툴 : XCode, Android Studio
- 작업툴 : IntelliJ
- 서버 : NodeJS
- DB : MySQL, MSSQL

## 3. 작업기간
- 개발 : 2개월
- 테스트 및 버그수정 : 3개월
- 요청 및 수정사항 반영 : 1개월

## 4. 프로젝트 스크린샷
<div>
<img src="https://user-images.githubusercontent.com/62881936/195543596-14df5652-672f-47d2-8c32-73c61b06b1a9.png" width="30%">
<img src="https://user-images.githubusercontent.com/62881936/195543646-9fd5a3fa-9102-4253-932d-8755db8b5fb4.png" width="30%">
<img src="https://user-images.githubusercontent.com/62881936/195543649-9ff97852-6c75-4b0d-9977-84da204e7651.png" width="30%">
<img src="https://user-images.githubusercontent.com/62881936/195543652-0eee9999-f46e-4caf-9b4a-36ed668a45d1.png" width="30%">
<img src="https://user-images.githubusercontent.com/62881936/195543656-7e141305-13a9-420a-9a9f-502fb3eaa27a.png" width="30%">
<img src="https://user-images.githubusercontent.com/62881936/195543660-b7c00450-4ba2-416d-9123-e01b1a6b9c66.png" width="30%">
</div>

## 5. 프로젝트 내 작업 파트
React Native 로 개발을 하여 iOS, Android 모두 출시를 해야 했기 때문에 iOS 쪽을 맡아서 하게 되었다.  
그 중 회원가입, 로그인, DB연결, 기타 라이브러리 사용, 업무 및 설정 부분을 맡아서 했다.

## 6. 프로젝트를 진행 하며 느낀점
이전에 사내 프로젝트가 React 프로젝트였기 때문에 크게 어려움이 없을 것이라 생각했다. 하지만 웹에서 사용하는 React와 모바일 기기로 포팅 되는 React Native와는 분명 다른 차이점이 많았다.  
처음 Hello World를 기기 내에서 띄우는 것 부터 해서 여러가지로 Native 적으로 연결되어야 하는 부분도 많았고, 특히 Notification 구현부분을 Swift로 작업을 해야하는 경우가 있었기 때문에 어려움이 있었다.  
그리고 웹과는 다르게 메모리 관리와 최적화도 신경을 써야 하는 부분이 있었기 때문에 state 보다는 memo 를 사용하여 작업을 하게 되었다.  
닮은 듯 닮지 않은 React 와 React Native였기 때문에 작업은 어려웠지만 보람차고 많은 것을 배울 수 있었던 프로젝트였던 것 같다.
