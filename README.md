# Sistema de Boletim Escolar em Java
**Sobre** <br>
Projeto avaliativo do SENAI de Java com interface gráfica sobre um Sistema de Boletim Escolar

>  ## _índice:_

- [Introdução](#introdução);
- [Objetivos do Projeto](#objetivos-do-projeto);
- [Funcionalidades](#funcionalidades);
- [Manual do Usuário](#manual-do-usuário);
- [Banco de Dados](#banco-de-dados);
- [Estrutura de Programação](#estrutura-de-programação);

>  ## _Introdução_
O projeto **"Sistema de Boletim Escolar"** foi desenvolvido para facilitar a gestão de notas e médias escolares. A motivação por trás deste projeto foi a necessidade de criar um sistema eficiente e automatizado para professores e alunos, possibilitando o acompanhamento do desempenho acadêmico. O sistema permite a aplicação de notas, o cálculo automático das médias e o gerenciamento de informações de professores, alunos e matérias.

<br>

>  ## _Objetivos do Projeto_
Realizar um sistema capaz de atribuir notas e calcular a média dos alunos. <br>

**1. Específicos:**
Desenvolver um sistema que permita a inserção, atualização e visualização de notas dos alunos, bem como o cálculo da média final de forma automática.

<br>

**2. Mensuráveis:**
O sucesso do projeto será avaliado pelo funcionamento correto das funcionalidades principais: cadastro, aplicação de notas, cálculo de médias e visualização dos dados.

<br>

**3. Atingíveis:**
Utilizando Java, PostgreSQL e outras ferramentas acessíveis, foi possível atingir os requisitos funcionais do sistema dentro do tempo e dos recursos disponíveis.

<br>

**4. Relevantes:**
O sistema atende à necessidade de automatização no controle de notas, agilizando o trabalho do corpo docente e oferecendo maior transparência para os alunos.

<br>

**5. Temporais:**
 O projeto foi desenvolvido ao longo de um período de uma semana, com cada funcionalidade sendo entregue de acordo com um cronograma pré-definido.

<br>

>  ## _Funcionalidades_

**1. Professor:**
- Aplicar e editar notas para os alunos de acordo com a matéria que leciona;
- Realizar o cálculo da média automaticamente a partir de três notas;
- Métodos CRUD (Criar, Ler, Atualizar, Deletar) das notas.

**2. Aluno:**
- Visualizar suas informações pessoais e notas por matéria;
- Filtrar matérias específicas.

**3. Admin:**
- Gerenciar (CRUD) cadastros de professores e alunos no sistema.

<br>

>  ## _Manual do Usuário_
O sistema é dividido em três níveis de acesso:<br><br>
**1. Admin:**
<br>
 - O administrador deve acessar o sistema com um login válido, onde ele poderá gerenciar as informações de professores e alunos. A interface de cadastro permite a inserção de novos professores e alunos.
<br><br>

### Login: 
<div align="center">
    <img src="escopo/manual_usuario/admin/login_adm.png" alt="Login do Admin" width="400vh">
</div>

<br>

### Cadastro de Professores:
<div align="center">
    <img src="escopo/manual_usuario/admin/cad_professor.png" alt="Cadastro de Professor" width="600vh">
</div>

<br>

### Cadastro de Alunos:
<div align="center">
    <img src="escopo/manual_usuario/admin/cad_aluno.png" alt="Cadastro de Aluno" width="600vh">
</div>

<hr>

**2. Professor:**
<br>
- Ao acessar o sistema, o professor pode aplicar notas, consultar o desempenho dos alunos e atualizar notas conforme necessário. O professor só pode alterar notas de alunos em suas matérias de especialização.
<br><br>

### Login: 
<div align="center">
    <img src="escopo/manual_usuario/professor/login_professor.png" alt="Login do Professor" width="400vh">
</div>

<br>

### Aplicar Nota para o Aluno:
<div align="center">
    <img src="escopo/manual_usuario/professor/aplicar_nota.png" alt="Aplicar a Nota" width="600vh">
</div>

<br>

### Seleção de Matéria Não-Especializada:
<div align="center">
    <img src="escopo/manual_usuario/professor/selecionar_materia_errada.png" alt="Seleção de Matéria" width="600vh">
</div>

<hr>

**3. Aluno:** 
<br>
- O aluno, após login, pode visualizar suas notas, filtrar as matérias e consultar sua média final.
<br><br>

### Login: 
<div align="center">
    <img src="escopo/manual_usuario/aluno/login_aluno.png" alt="Login do Aluno" width="400vh">
</div>

<br>

### Visualizar Informações do Aluno:
<div align="center">
    <img src="escopo/manual_usuario/aluno/visualizar_boletim.png" alt="Visualizar Informações" width="600vh">
</div>

<hr>

### _Diagramas:_

**_Fluxograma de Uso:_**

<br>

**_Fluxograma de Fluxo:_**

<br>

>  ## _Banco de Dados_

### _Diagramas:_

**_Fluxograma de Classe:_**

<br>

>  ## _Estrutura de Programação_
O sistema foi desenvolvido utilizando as seguintes tecnologias:

**Java**
<br>
Linguagem de programação principal utilizada para implementar toda a lógica de negócios do sistema. A sua vantagem é ser uma linguagem ersátil, permite o desenvolvimento de aplicações robustas e escaláveis.

<hr>

**PostgreSQL**
<br>
Banco de dados relacional utilizado para armazenar as informações dos professores, alunos, matérias e notas. A escolha por PostgreSQL se deu por sua robustez e capacidade de lidar com grandes volumes de dados. Suas principais vantagens são: Programa gratuito, open-source, e possui grande suporte a transações ACID e integração com Java.

<hr>

**Github**
<br>
Utilizado para versionamento de código, facilitando o trabalho colaborativo e o controle de versões ao longo do desenvolvimento do projeto. Ele oferece controle total do código, permitindo o histórico de mudanças e trabalho colaborativo.

