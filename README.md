# Sistema de Gerenciamento de Estúdio de Tatuagem

O **Sistema de Gerenciamento de Estúdio de Tatuagem** tem como objetivo proporcionar o controle completo sobre as operações de um estúdio, incluindo o gerenciamento de tatuadores, clientes e sessões de tatuagem. O sistema permitirá o registro, consulta e atualização das informações relacionadas a cada entidade, além de gerar relatórios formatados com base em critérios específicos.

## Estruturas de Dados

### Tatuador:
- **Registro** (único)
- **Nome**
- **Anos de Experiência**
- **Especialidade**

### Cliente:
- **CPF** (único)
- **Nome**
- **Idade**
- **Tipo de Pele**
- **Número de Tatuagens**

### Sessão:
- **ID da Tatuagem** (único)
- **Data da Sessão**
- **Tatuador**
- **Cliente**
- **Valor**

## Campos de Consulta e Alteração

- **Tatuador**: Consulta e alteração através do **Registro**
- **Cliente**: Consulta e alteração através do **CPF**
- **Sessão**: Consulta e alteração através do **ID da Tatuagem**

## Consulta de Sessão

Ao consultar uma **sessão**, os dados exibidos serão os seguintes:
- **ID da Tatuagem**
- **Data da Sessão**
- **Valor**
- **Registro do Tatuador**
- **Nome do Tatuador**
- **Nome do Cliente**
- **CPF do Cliente**

## Geração de Relatório

O sistema também será capaz de gerar um **relatório em formato texto** com base nas sessões de tatuagem realizadas em um intervalo de tempo determinado. O usuário fornecerá uma **data inicial** e o sistema gerará um relatório com as seguintes informações:

- **ID da Tatuagem**
- **Data da Sessão**
- **Valor**
- **Nome do Cliente**
- **CPF do Cliente**
- **Idade do Cliente**
- **Nome do Tatuador**
- **Registro do Tatuador**
- **Especialidade do Tatuador**

Esse relatório incluirá todas as sessões realizadas entre a data fornecida e a data atual.
