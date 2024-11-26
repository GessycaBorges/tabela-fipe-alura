# Desafio Java - Consultando a tabela FIPE
Implementar uma aplicação para consultar o valor médio de veículos (carros, motos ou caminhões) de acordo com a tabela FIPE.

## 🔨 Objetivos do projeto
- O objetivo do projeto é ter um fluxo similar ao que é feito no [site de consulta da tabela FIPE](https://veiculos.fipe.org.br/), porém com algumas melhorias.
- Criaremos um projeto Spring com linha de comando, utilizando a classe Scanner para fazer interações com o usuário via terminal.
- Solicitaremos que o usuário digite o tipo de veículo desejado (carro, caminhão ou moto).
- Feito isso, listaremos todas as marcas daquele tipo de veículo, solicitando que o usuário escolha uma marca pelo código.
- Após essa escolha, listaremos todos os modelos de veículos daquela marca.
- Solicitaremos que o usuário digite um trecho do modelo que ele quer visualizar, por exemplo PALIO.
- Listaremos apenas os modelos que tiverem a palavra PALIO no nome.
- Usuário escolherá um modelo específico pelo código e, diferente do site, já listaremos as avaliações para TODOS os anos disponíveis daquele modelo.

## Observações:
- Para realização do desafio faremos o consumo de uma API, documentada nesse [link](https://deividfortuna.github.io/fipe/).
