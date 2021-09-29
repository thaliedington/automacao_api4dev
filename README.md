# Automatizando API com Robot Framework
## Sobre

##### Teste de Consumi de API https://www.4devs.com.br/ferramentas_online.php

##### Utilizando o método POST
##### As chaves e valores: acao=gerar_pessoa, pontuacao=N, sexo=H

##### E as seguintes validações:
##### 1. Validar o campo Status Code (Resultado esperado deve ser 200)
##### 2. Validar se o campo Idade consta do ResponseBody (Resultado esperado deve ser Sucesso)
##### 3. Validar se o valor do campo sexo do ResponseBody é igual a Masculino (Resultado esperado deve ser Sucesso)
##### 4. Armazenar o campo CPF do ResponseBody em uma variável nomeada CPF.
##### 5. Limpar a variável CPF.

## Script criado com Robot Framework com as bibliotecas:

##### RequestsLibrary
##### Collections
##### JSONLibrary

## Pré-requisitos

##### Python instalado
##### Robot Framework instalado
##### RequestsLibrary (Robot)
##### JSONLibrary
