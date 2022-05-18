# trialGraphQL
myFirstGraphQL


/* 
설치방법 : 
아폴로 서버를 사용한다.
npm init -y (node repository 초기화)
1. npm install apollo-server graphql
2. npm install nodemon -D
3. server.js / .gitignore 파일 생성
4. .gitignore에서 node_modules/를 입력하고 새로운 깃 리포지토리를 초기화해준다. (git init)
5. package.json에서 다음과 같이 수정한다.
 script 태그 "test" => dev (사용자가 원하는 내용으로 수정 가능하다.)
 dev 옆에는 nodemon server.js명령어를 작성한다.
 하단부에 "type":"module"을 작성해주고 server.js에서 아폴로서버를 사용할 수 있다.
6. server.js파일에 아폴로서버가 자동완성으로 나와주면 설치는 성공
 import {ApolloServer, gql} from "apollo-server"

실행방법
:  npm run dev으로 nodemon을 실행 시킬 수 있으며 ctrl+C으로 종료가 가능하다.
리액트 서버를 실행시키고 종료시키는 방법하고 동일하다.

쿼리 처리 방법 : 
 데이터를 받도록 하고 싶다면 Query Type안에 있어야한다.
 데이터를 보낸 데이터가 데이터베이스로 간다거나 수정 삭제를 해야한다면 mutation안에 있어야한다.
*/
