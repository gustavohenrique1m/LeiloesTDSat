💻 

**Leiloes TDS UC11 - Atividade 1**💻
# Sistema Desktop para Casa de Leilões

## Status do projeto



## Tecnologias

- **Java** (linguagem de programação)
- **NetBeans** (ambiente de desenvolvimento)
- **Java Swing / JFrame** (interface gráfica desktop)
- **MySQL** (banco de dados)
- **MySQL Workbench** (modelagem e administração do banco)
- **JDBC** (conexão entre o Java e o MySQL)
- **Git e GitHub** (versionamento de código)
- **UML** (diagrama de classes)

## Time de desenvolvedores

[Gustavo henrique]
## Objetivo do software

Informatizar as rotinas de uma casa de leilões, substituindo o controle manual dos itens leiloados por um sistema desktop com banco de dados. O sistema deve permitir cadastrar os produtos que entrarão em leilão, consultar tudo o que está cadastrado, registrar a venda de um produto e consultar o histórico de itens vendidos.

## Funcionalidades do sistema (requisitos)

- [x] Abrir o sistema na tela de cadastro de produtos
- [x] Cadastrar um produto (nome e valor) no banco de dados
- [x] Exibir mensagem informando se o cadastro foi realizado com sucesso ou não
- [x] Listar todos os produtos cadastrados (id, nome, valor e status)
- [x] Vender um produto a partir da listagem, alterando o status para "Vendido"
- [x] Listar, em tela própria, apenas os produtos vendidos
- [x] Navegar entre as telas de cadastro, listagem e vendas

## Estrutura do projeto

Classe e Função 

 `cadastroVIEW`  Tela principal, cadastro de produtos 
 `listagemVIEW`  Lista de produtos e venda 
 `vendasVIEW`  Lista de produtos vendidos
`ProdutosDTO`  Representa um produto (id, nome, valor, status) 
| `ProdutosDAO` | Operações no banco de dados |
| `conectaDAO` | Conexão com o MySQL |
