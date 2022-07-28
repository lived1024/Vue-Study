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
- ### Vetur
    Visual Studio Code 한글화


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

# 프로젝트 기본 설정
## 대상소스
[패스트캠퍼스 강의 원본](https://github.com/ParkYoungWoong/webpack-template-basic)

## 설정 스크립트
```
/* npx degit를 이용하게 되면 git clone처럼 소스를 가져올 수 있다!!
 * git clone과 차이점은 단순히 소스만 가져옴 - history, branch 정보 등을 가져오지
 * 않는다.
 * 
 * npx degit                                 git clone과 비슷한 명령어
 * ParkYoungWoong/webpack-template-basic     대상 저장소
 * vue3-webpack-template                     저장할 폴더
 * 해당 명령어를 실행 후, vue3-webpack-template 폴더가 생성되어 소스가 다운되어있다.
*/
$ npx degit ParkYoungWoong/webpack-template-basic vue3-webpack-template
```