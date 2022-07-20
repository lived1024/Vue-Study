# Visual Studio Code
## 사용 플러그인
- ### Korean(사용법) Language Pack for Visual Studio Code
    Visual Studio를 한글로 바꿔주는 플러그인
- ### Beautify
    자동 줄맞춤 기능을 사용할 수 있게 해주는 플러그인

    - 사용방법  
    [파일] - [기본 설정] - [바로가기키] - 'HookyQR.beautify' 검색 후 단축키 설정  
    ex) Ctrl  + Shift + L
- ### Auto Rename Tag
    태그 변경 시 쌍으로 이루어진 태그를 자동으로 변경


# Node.js
## 1. 설치한 패키지
### PARCEL-BUNDLER 
 - 아주 간편하게 번들링 해준다.
```
$ npm install parcel-bundler -D

// package.json > scripts 에 아래와 같이 설정
/* "scripts": {
 *   "dev" : "parcel index.html",               --> 개발자모드
 *   "build" : "parcel build index.html"        --> 패키지 빌드
*/ },
$ npm run dev
$ npm run build
```
### LODASH 
- JavaScript에서 배열 안의 객체들의 값을 handling(배열, 객체 및 문자열 반복 / 복합적인 함수 생성) 할 때 유용
```
$ npm install lodash
```

## 2. 프로젝트 초기 시작 설정 명령어
```
$ npm install -y
```