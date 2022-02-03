| Número | Caso de uso | Objetivo do caso de teste | Entradas | Resultados esperados |
| ------| ---- | ----- | ----- | ----- |
| 1 | Cadastrar usuário | Cadastramento com um novo e-mail | E-mail: joaosilva@gmail.com | Mensagem de confirmação de envio de e-mail de inscrição no sistema | 
| 2 | Cadastrar usuário | Cadastramento com um e-mail já registrado pelo sistema | E-mail: joaosilva@gmail.com | Mensagem de erro informando que o e-mail já está em uso |
| 3 | Cadastrar projeto | Cadastrar um novo projeto | Nome do projeto: E-commerce Brasil, Gerente: Joao Silva | Mensagem de cadastro realizado com sucesso |
| 4 | Cadastrar projeto | Cadastrar um projeto com um nome repetido | Nome do projeto: E-commerce Brasil, Gerente: Maria Rodrigues | Mensagem de erro, solicitando ao usuário escolher outro nome de projeto |
| 5 | Gerar relatório | Gerar um relatório de um projeto devidamente configurado | Selecionar o botão gerar relatório do projeto | Mensagem de download iniciando em instantes |
| 6 | Gerar relatório | Gerar um relatório de um projeto que não foi configurado | Selecionar o botão gerar relatório de um projeto com status INICIANDO | Mensagem de erro orientando o usuário a preencher o projeto com as mais informações |
