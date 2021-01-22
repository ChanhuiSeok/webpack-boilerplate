# webpack-boilerplate
webpack, babel, node.js 모듈 등을 추후에 재사용하기 위한 boilerplate code 입니다.

### webpack 설정
 * webpack.config.js 파일
 * 엔트리 포인트 : `"./public/js/app.js"`
 * html-webpack-plugin, copy-webpack-plugin 사용
 * webpack-dev-server 활용 (`npm run dev`)
 
### babel 설정
 * babel.config.json 파일
 * `@babel/plugin-proposal-class-properties` 추가
   * js의 최신 문법들, 즉 실험 단계에 있는 것까지 트랜스파일링하기 위함
