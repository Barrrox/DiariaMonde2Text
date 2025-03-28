# DiariaMsgCreator

Autor: Matheus Barros
Data de concepção: 28/03/2025

## O projeto 
A diária de hospedagem é simples e há poucas informações que precisam ser alteradas no envio das mensagens. A ideia é implementar um gerador de mensagens de texto que serão copaidas para serem enviadas no Octadesk para clientes compradores de diárias de hospedagens. 

## Funcionamento

1. Importar a planilha de diarias de hospedagem 

O usuário do DiariaMsgCreator irá importar a planilha (no formato .xlsx) do dia de diárias de hospedagem do monde para o arquivo *entrada/planilha_diarias.xlsx*. A planilha precisa conter as informações do nome do passageiro e data da viagem. 

Você também pode apenas importar a planilha para a pasta entrada e alterar o nome da planilha para *planilha_diarias.xlsx*. 

2. Dar Run

Executar o arquivo criar_mensagens.ipynb

3. Copiar mensagens criadas

As mensagens recém-criadas estarão na pasta *Mensagens criadas*

Será criado um arquivo para cada passageiro

## Exemplo

Se o nome do passageiro era Fulano Ciclano da Costa, ao executar o código, haverá um arquivo chamado *Fulano Ciclano da Costa* na pasta *Mensagens criadas* com o seguinte texto (à melhorar):

```
Olá Fulano Ciclano da Costa!

Faltam 3 dias para a sua hospedagem no dia 31/03/2025. 
```

## Observações

É recomendado excluir cada arquivo criado dentro de *Mensagens criadas* após enviar as mensagens, como forma de indicar que aquela mensagem não é mais útil.

É recomendado excuir a planilha importada depois de utilizá-la ou ao final do dia como forma de segurança. 
