# movieql
Movie API with Graphql
yarn add graphql-yoga
생성된 package.json 파일에 
  "scripts": {
    "start": "nodemon --exec babel-node index.js"
  }
  추가
  
  터미널에 yarn global add nodemon 입력
  
  yarn start 실행해서 정삭적으로 index.js에 넣은 console.log가 나오는지 변경시 자동으로 재시작을 하는지 확인한다.
  
  터미널에 yarn global add babel-cli 입력
  .babelrc 파일 생성 
  .babelrc 파일에   "presets": ["env","stage-3"] 입력  
  터미널에 yarn startyarn add babel-cli babel-preset-env babel-preset-stage-3 --dev 입력
  yarn start 
  
  
