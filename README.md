# Aplicando Formas Normais em Bancos de Dados
Este repositório contém um projeto prático de modelagem e normalização de banco de dados, desenvolvido com o objetivo de aplicar e demonstrar o uso das Formas Normais (1FN a 5FN) na estruturação de dados relacionais.
### 💡 Objetivo
O projeto tem como finalidade simular, de forma didática e aplicada, a normalização de um banco de dados fictício. O foco é compreender e aplicar as boas práticas de modelagem de dados para eliminar redundâncias, evitar anomalias e garantir a integridade dos dados.
### 📋 O que foi feito
Ao longo deste exercício, a estrutura original da tabela cliente foi progressivamente transformada, obedecendo às seguintes Formas Normais:
* 1ª Forma Normal (1FN): Separação de dados não atômicos, criando a tabela telefone para permitir múltiplos números por cliente;


* 2ª Forma Normal (2FN): Eliminação de dependências parciais com a criação de uma tabela de endereço;


* 3ª Forma Normal (3FN): Remoção de dependências transitivas, separando cidade e estado em tabela própria;


* 4ª Forma Normal (4FN): Tratamento de multivalores independentes, como múltiplos e-mails;


* 5ª Forma Normal (5FN): Separação de dependências múltiplas complexas, como o relacionamento entre cliente e produto, com tabela intermediária para representar interesses.


### 🔧 Tecnologias utilizadas
* SQL (modelo relacional)


* Markdown para documentação do projeto


### 🧠 Aprendizados
Este exercício reforçou a importância da normalização em bancos de dados e sua aplicação prática em cenários reais. Com ele, aprofundei meus conhecimentos em:
* Identificação e resolução de redundâncias;


* Modelagem lógica e conceitual;


* Boas práticas de organização de dados relacionais.


## 💼 Relevância profissional
Este projeto demonstra minha capacidade de aplicar teoria em prática com foco em qualidade de dados, organização estrutural e escalabilidade de sistemas. É uma amostra do meu comprometimento com padrões de desenvolvimento robustos e estruturados — habilidade essencial para qualquer posição que envolva modelagem ou manipulação de dados.


