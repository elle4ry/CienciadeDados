Projeto de Limpeza e Organização de Dados para MegaSuper Vendas

Este repositório descreve o processo de transformação de dados brutos do e-commerce fictício MegaSuper Vendas, que estava enfrentando dificuldades com dados desestruturados e inconsistentes. O objetivo do projeto é limpar e estruturar essas informações, criando uma base de dados pronta para análises precisas e eficientes.

⭕ Contexto do Projeto
A base de dados original apresentava diversas falhas críticas, como:

Valores ausentes em campos essenciais;

Nomes de produtos inconsistentes e mal formatados;

Erros nos cálculos da coluna "Total";

Duplicação de registros;

Informações de CEPs e estados incorretas;

Tipos de dados errôneos em algumas colunas.

Este projeto busca corrigir essas falhas por meio de um processo de limpeza, padronização e validação, transformando o conjunto de dados em algo confiável e adequado para análises avançadas.

⭕ Tecnologias Empregadas
Python 3.10+ – Linguagem de programação escolhida.

pandas – Para manipulação e limpeza de dados.

numpy – Para operações numéricas e manipulação de arrays.

datetime – Para conversão e formatação de datas.

os – Para manipulação de arquivos e diretórios.

Git/GitHub – Para controle de versão e colaboração no desenvolvimento.

⭕Passos Seguidos Durante a Limpeza de Dados
🔹 Carregamento Inicial e Preparação
Leitura do arquivo .csv com encoding UTF-8.

Renomeação das colunas para o padrão snake_case.

🔹 Tratamento de Dados Incompletos
Substituição de valores ausentes (NaN) por padrões como 0 ou "desconhecido".

Conversão de colunas de data/hora para formatos consistentes.

🔹 Padronização dos Dados
Normalização de texto para garantir uniformidade (todos em minúsculas).

Utilização de expressões regulares para padronizar os nomes dos produtos.

Validação e formatação correta dos CEPs.

🔹 Correção de Cálculos
Recalculo da coluna "Total" com a fórmula: valor * quantidade + frete.

Remoção de registros com valores inválidos ou inconsistentes.

🔹 Eliminação de Duplicatas
Identificação e exclusão de registros duplicados.

Ajuste dos índices para garantir a integridade dos dados.

🔹 Relatório Final
Geração de um relatório detalhado no console, apresentando as estatísticas do processo de limpeza realizado.
