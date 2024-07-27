
# Star Schema para Análise dos Dados

## Uma breve descrição sobre o projeto

### Objetivo
O objetivo deste projeto é criar um diagrama dimensional - star schema - com base no diagrama relacional fornecido. O foco da análise é nos dados dos professores, incluindo cursos ministrados e departamentos aos quais pertencem.

### Escopo do Projeto
Este projeto concentra-se na criação de uma tabela fato e várias tabelas de dimensões para facilitar a análise dos dados relacionados aos professores. Note que dados sobre alunos não são incluídos neste escopo.

### Estrutura do Esquema Estrela

Considerações de Modelagem
Para compensar a falta de dados de datas no modelo relacional original, supomos que temos acesso a informações sobre as datas de oferta dos cursos e disciplinas. A granularidade das datas pode variar de acordo com a necessidade da análise, podendo incluir diferentes níveis de detalhes, como ano, mês, dia, trimestre, etc.

Como Utilizar este Repositório
Clone o repositório:

```sh
Copiar código
git clone https://github.com/seu-usuario/seu-repositorio.git
```

Acesse o diretório do projeto:

```sh
Copiar código
cd seu-repositorio
```
### Arquivos

Abra o arquivo universidade_model.mwb para visualizar e modificar o esquema estrela conforme necessário.

Utilize uma ferramenta de banco de dados para executar o script SQL e criar as tabelas no seu ambiente de banco de dados preferido.

### Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.
