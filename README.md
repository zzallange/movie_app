# Movie App

React JS Start

# Set Up

1. node -v, npm -v check (No file -> Download)
2. npx install (npm install npx -g)
3. git exist check (No file -> Download)
4. cd Documents
   npx create-react-app movie_app
   (reference: https://github.com/facebook/create-react-app)
5. npm start
   😎 success => Local / Network address offer
   (Local = my computer / Network = wifi)
6. git init 저장소 초기화 (url setting)
   git origin check -> git remote -v
   기존경로가 다를경우 기존경로 리포지토리 제거 git remote remove origin
7. git remote add origin (your github repository url)
8. git add . -> git commit -m "" -> git push origin master

# React

<div id="root"></div> 안에 element를 넣는 역할을 담당
src > index.js에 적힌 ReactDOM.render에 root를 가져온다고 적혀있다
