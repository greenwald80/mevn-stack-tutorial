$npm i -g mevn-cli
$mevn init yt-test
=> nuxt.js => universal => node => express

$cd yt-test && mevn serve

server:
http://localhost:9000/api

client:
http://localhost:3000

ADD mongodb:
$mevn generate => CRUD boilerplate => MongoURI enter

POSTMAN
GET http://localhost:9000/api
POST http://localhost:9000/api => Body => RAW => JSON => {"name":"Alex","age":"41"}
DELETE http://localhost:9000/api/60fee03be5e6086ba72d9eb4


Deploy:
$mevn deploy => server=> mevn-name => mongodb path


https://www.youtube.com/watch?v=9BbfQN1z2qU