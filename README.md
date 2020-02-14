# Desafio Nexaas para pessoa desenvolvedora em Ruby

Ficamos felizes que tenha chegado nesta etapa do processo seletivo para pessoa desenvolvedora em Ruby. Nosso desafio é a construção de uma API Rest, obrigatoriamente você deve implementar uma solução com Ruby (preferencialmente utilizando Rails).

Crie uma API Rest que faça o gerenciamento de estoque de loja. As entidades devem ser: 
Product: informações de produto (id, nome e preço de custo, por exemplo)
Store: Informações sobre a loja (id, nome e endereço, por exemplo)
StockItem: Deve relacionar uma loja a um produto e armazenar a quantidade de itens em estoque


As operações devem ser:
- Cadastrar, alterar, excluir e pesquisar produto (apenas por ID) 
- Cadastrar, alterar, excluir e pesquisar loja (apenas por ID) 
- Criar estoque de um produto em uma loja (relacionar loja e produto e inserir uma quantidade inicial de itens)
- Adicionar itens de um produto ao estoque
- Retirar itens de um produto do estoque

O que você deve nos entregar:
- Código fonte no Github com documentação no readme ou wiki sobre como rodar localmente a aplicação
- Utilize banco relacional
- Aplicação rodando no Heroku
- Documentação de como utilizar os endpoints

O que vamos avaliar:
- Solução adotada, principalmente a questão de adicionar e retirar itens do estoque (imagine um cenário de concorrência)
- Cobertura de testes e a qualidade dos testes (utilize o RSpec)
- Qualidade de código
- Conceitos avançados de orientação a objetos (nada de fat model ou controllers com regras de negócio, por favor)
- Estrutura do banco de dados (índices, chave estrangeiras, chaves únicas… use um banco relacional e todo seu poder)
- Verbos e status code dos endpoints (utilize os padrões HTTP)
- Como os erros são tratados
