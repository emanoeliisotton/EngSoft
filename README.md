# Sistema de gestão de estoque para centros de saúde - GECES

Bem-vindo ao projeto da disciplina EngSoftI!

## Visão Geral

Este repositório contém o código-fonte e a documentação para o Sistema de gestão de estoque para centros de saúde - GECES. Este sistema foi desenvolvido para simplificar e otimizar o processo de compra e recebimento de materiais médicos e de saúde em estabelecimentos de saúde.

## Descrição do projeto :bookmark_tabs:	

Tem como objetivo realizar a gestão de solicitação e recebimento de materiais dentro de um estabelecimento de saúde. A interação no sistema ocorre entre almoxarife do estabelecimento e fornecedor de materiais. O almoxarife faz a solicitação de compra dos materiais desejado e a envia para o fornecedor e o mesmo dentro do sistema recebe tal solicitação de compra. O fornecedor deve fazer a separação dos itens e os envia-los para o estabelecimento, ao receber os itens, o estabelecimento deverá fazer a conferência dos mesmos no sistema e finalizar a compra.

## Funcionalidades do projeto

- Solicitação de Compra de Materiais
- Gerenciamento de Solicitações de Compra
- Recebimento de Solicitações pelos Fornecedores
- Separação e Envio de Materiais pelos Fornecedores
- Rastreamento em Tempo Real
- Conferência de Materiais
- Relatórios e Análises 
- Notificações e Comunicação
- Segurança e Autenticação
- Personalização

## Requisitos

Antes de começar, verifique se seu ambiente atende aos seguintes requisitos:

- **Ambiente Web**: Este sistema é baseado na web e requer um servidor web com suporte a PHP, MySQL e uma conexão com a Internet.

- **Navegador Web**: Para acessar o sistema, você precisará de um navegador da web moderno, como Google Chrome, Mozilla Firefox ou Safari.

- **Banco de Dados**: É necessário ter um servidor MySQL configurado.

## Instalação

1. Clone este repositório em seu servidor web:

```bash
gh repo clone emanoeliisotton/EngSoft
```

2. Crie um banco de dados MySQL e importe o arquivo SQL fornecido no diretório `database` para configurar as tabelas necessárias.

3. Configure as credenciais do banco de dados no arquivo `config.php` localizado na raiz do projeto.

4. Abra um navegador da web e acesse o sistema através do URL do servidor onde o projeto foi clonado.

## Uso

Após a instalação e configuração do sistema, siga estas etapas para começar a utilizá-lo:

1. Faça login no sistema usando suas credenciais.

2. Como **Almoxarife**:
   - Crie solicitações de compra especificando os materiais desejados e suas quantidades.
   - Acompanhe o status das solicitações em tempo real.
   - Conferência dos materiais recebidos no sistema.

3. Como **Fornecedor**:
   - Receba as solicitações de compra dos almoxarifes.
   - Separe e envie os materiais solicitados.
   - Atualize o status das solicitações à medida que você processa os pedidos.

4. Utilize os recursos de relatórios e análises para tomar decisões informadas relacionadas à gestão de materiais.

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir para este projeto, siga estas etapas:

1. Fork este repositório.
2. Crie uma branch para a sua contribuição: `git checkout -b alteracoes`.
3. Faça as alterações necessárias.
4. Faça commit de suas alterações: `git commit -m 'Adicionando funcionalidade X'`.
5. Faça push para a branch: `git push origin alteracoes`.
6. Abra um Pull Request descrevendo suas alterações.
  
## Status do projeto

Em processo de planejamento.

## Links relativos 

[Modelagem de software](https://github.com/emanoeliisotton/EngSoft/blob/main/Modelagem%20de%20software%20-%20GECES%20-%20Aula%2023.08.23.pdf)
