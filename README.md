# 리액트 프로젝트 시작하기
## 시작 전에
### 추천 소프트웨어
1. VS Code
2. iTerm
3. Google Chrome
4. Github desktop

### 필수 준비물
####  Node, npm
1. Mac 설치:
- Node [설치](https://nodejs.org/en/download/)
Node 설치 후 다음 커맨드를 터미널에 입력합니다. (mac 용)
    ```sh 
    sudo npm install npm --global
    ```

2. Windows 설치 :
다음 [블로그 포스트](https://radixweb.com/blog/installing-npm-and-nodejs-on-windows-and-mac#windows)를 참고하세요

Node, npm 설치 확인 방법:
터미널에 다음 커맨드를 입력 할 때 버전을 나타내야 합니다.
1. ```sh node -v ```
2. ```sh npm -v ```


## 프로젝트 시작하기

### 프로젝트 복사
Github Repo에서 `<> Code` 버튼을 클릭하여 repo를 복사합니다.
![프로젝트](https://github.com/sujilee91/pair-coding/blob/main/blob/copy_code.png)

- github desktop 프로그램이 있다면 "Open with Github Desktop" 사용을 추천
- https 를 이용하여 로컬 컴퓨터에 다운로드 ([참고](https://sosoeasy.tistory.com/318))


### 프로젝트 실행하기

다운로드 받은 파일 오른쪽 마우스 클릭 후 `New terminal at folder` 클릭 (mac) 
혹은 
shift + 오른쪽 마우스 클릭 (windows) 
하여 다운로드를 완료 한 해당 프로젝트의 터미널로 이동합니다.

터미널에서 다음 커맨드를 실행합니다.
```sh
npm install
```
설치 커맨드 완료 후 다음 커맨드를 실행합니다.
```sh
npm start
```

정상으로 작동시 자동으로 `http://localhost:3000` 페이지가 로드 되어야 합니다.

### 프로젝트 설명
React 와 Open RESTful API - 날씨, Quote 를 이용한 Single Page Application 을 구현 하는 프로젝트 입니다.

#### Techstack
- React
- CSS

#### 개발 과정
1. 디렉토리 구성 하기
현재 프로젝트 내 디렉토리를 다음과 같이 구성 해 줍니다.
    ```sh
        src
        |-components
        |-|- Weather.js
        |-|- Quote.js
        |-functions
        |-|- constants.js
        |-|- useFetchWeather.js
        |-|- useFetchQuote.js
        
    ```

2. 깃헙 branch,commit,push,pull,merge 이해하기
- branch
- commit
- push
- pull
- merge