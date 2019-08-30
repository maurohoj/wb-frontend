#Informações uteis

#CORS
tive de adicionar esses parametros nos 2 backends pois estavam dando conflito de segurança
var cors = require('cors');
app.use(cors());

npm install cors --save
utilize esse comando para adicionar o cors

#Conexão MongoDB
mongodb+srv://dbuser:<password>@mongodb-dtkfx.mongodb.net/test?retryWrites=true&w=majority
userdb: dbuser
pass:   dbuser

#Chaves GitHUB
Client ID: e92dd3fd5ab684841feb
Client Secret: ff2c3a4610529d6a3a4b55a2b9ef9b759fdb5cf4