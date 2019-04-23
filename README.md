##Programa  ClI de CRUD de Herois baseado no treinamento node(Underline)



####Options:

 - -V, --version        output the version number
 - -i, --id [value]     Id do Heroi
 - -n, --name [value]   Nome do Heroi
 - -p, --poder [value]  Poder do Heroi
 - -c, --cadastrar      Cadastrar o Heroi
 - -l, --lista          Listar um Heroi
 - -d, --delete         Deletar um Heroi
 - -u, --update         Deletar um Heroi
 - -h, --help           output usage information

####Instaler as dependecias

`npm install`

####Create

`node index.js -c -n flash -p Speed`

####Delete

`node index.js -c -n flash -p Speed`

####List

`node index.js -l -n flash`
use o nome que deseja buscar

####Update

`node index.js -u -n Batman -p Many -i 2`

voce pode passar apenas os paramentro que deseja atualizar sendo obrigatorio apenas o `-i ou --id`
