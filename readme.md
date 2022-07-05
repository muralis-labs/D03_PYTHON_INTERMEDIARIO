# Desafio Python

# Objetivo

> Esse desafio tem por objetivo medir as capacidades técnicas para
> programação de ETL usando Python.

# Stack tecnológico

> Python versões mais recentes.

# Nível

> Intermediário -- Capacidade de interpretar os requisitos do cliente e
> implementar utilizando Python.

# Problema

A.  **Criar uma base de dados (BD01) (em qualquer gerenciador de banco
    de dados)**

    a.  Criar uma tabela chamada "funcionarios" contendo os seguintes
        campos:

        1.  ID

        2.  Nome

        3.  RG

        4.  CPF

        5.  Data_admissao

        6.  Data_hora_alteracao_do_registro

        7.  CEP

    b.  Popular a tabela com pelo menos 10 registros completos.

B.  **Criar uma outra base de dados (BD02) (em qualquer gerenciador de
    banco de dados)**

    a.  Criar uma tabela chamada "funcionarios_fabrica" contendo os
        seguintes campos:

        1.  ID

        2.  NOME

        3.  RG

        4.  CPF

        5.  Data_admissao

        6.  Data_hora_alteracao_do_registro

        7.  CEP

        8.  ENDERECO

        9.  BAIRRO

        10. CIDADE

    b.  Popular a tabela com os mesmos 10 registros, porém, preencher
        somente os campos ID e NOME, deixando os demais campos nulos.

C.  **Criar um programa em PYTHON capaz de carregar os funcionários
    contidos no banco BD01 para a tabela "funcionarios \_fabrica" do
    BD02, de forma que sejam atualizados através do campo ID.**

    a.  A data de alteração do registro da tabela "funcionarios_fabrica"
        deverá ser a data e hora do momento da movimentação do registro.

    b.  Os campos (ENDERECO, BAIRRO, CIDADE), deverão ser preenchidos
        através de consulta de uma api de CEPs. Ex. Viacep.com.br.

    c.  O campo CODIGO deverá ser randômico e não deve se repetir.

D.  **Criar um programa em PYTHON capaz de gerar api**

    a.  Criar endpoints respectivos com as operações de CRUD para
        realizar as operações na tabela "funcionarios_fabrica"

E.  **Deverá ser gerado logs, onde os logs anteriores a dois dias sejam
    deletados.**

F.  **Utilize uma ferramenta de consumo de APIs para consumir todos os
    endpoints gerados.**
