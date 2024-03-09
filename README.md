 
# node.js 설치
    - 설치 확인
    - vscode 터미널 : ctrl+shift+`
    - node.js 버전 확인 : node --version
# 리액트 => create-react-app 설치
    - npm install -g create-react-app
    - npm i -g create-react-app
# 리액트 프로젝트 생성
    - npx create-react-app 프로젝트이름

# 프로젝트 실행
    - dir / ls / cd 리눅스 명령어
    - cd 프로젝트명
    - npm start 프로젝트 실행 명령어 -> package.json 에 있음
    - http://127.0.0.1:3000/ = http://localhost 


    ** 참고 - 아이피 1개당 접속가능한 pc는 256개 // 포트번호 사용하는 이유 ** 

# 프로젝트에 본인 이름 타이틀 쓰기~

# App.js -> App.jsx 로 변환

# 컴포넌트 만들기
    // 클래스 방식
    // 함수 방식
    1. 컴포넌트 설계
        -WrapComponent.jsx
            - [css] 폴더
                - HeaderComponent.css
                - MainComponent.css
                - FooterComponent.css

            - [wrap] 폴더
            - HeaderComponent.jsx
            - MainComponent.jsx
                - [main] 폴더
                    - Section1Component.jsx
                    - Section2Component.jsx
                    - Section3Component.jsx
                    - Section4Component.jsx
                    - Section5Component.jsx

                    - [css] 폴더       
                        - SectionPublic.css
                        - Section1Component.css
                        - Section2Component.css
                        - Section3Component.css
                        - Section4Component.css
                        - Section5Component.css

            - FooterComponent.jsx

```js
    //WrapComponent.jsx

    function WrapComponent(){
        return (
            // 리턴문에는 하나의 div 만 있어야 한다.
            <div id="wrap">
                <h1>여기는 WrapComponent 입니다.</h1>
            </div>
        )
    }   

    // 생성된 컴포넌트 외부로 내보내기
    export default function WrapComponent(){
        return (
            // 리턴문에는 하나의 div 만 있어야 한다.
            <div id="wrap">
                <h1>여기는 WrapComponent 입니다.</h1>
                
            </div>
        )

    }

    // 생성된 컴포넌트 가져오기(사용가능)
    import WrapComponent from './WrapComponent'

    // 가져온 컴포넌트 사용하기
    root.render(

        <WrapComponent/> // root.render 에 추가해주기.
    );


```

## 로드모듈 없는 프로젝트 사용하기
    - 로드모듈 생성하기
    - npm install




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
