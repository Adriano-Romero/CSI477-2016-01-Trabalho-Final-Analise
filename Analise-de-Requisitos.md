# Digital Nutri: Análise de Requisitos

## 1. Introdução
Tem se tornado cada vez maior a busca por alimentação saudável. Alimentos com baixo teor calórico, sem glúten ou sem lactose. Pensando nesse público, e na tentativa de influenciar cada vez mais pessoas a se alimentarem de forma saudável, está loja se destina a fornecem diversas iguarias que se adequam à vida saudável.

Dentre nossos produtos, encontram-se óleos de coco, barras de cereal ou de frutas, doces sem lactoses e temperos sem adição desal ou produtos inorgânicos.

Nosso foco é atender ao público que deseja manter uma dieta alimentar saudável. E incentivar a transformação dos hábitos alimentares de cada vez mais pessoas. Nosso site conta também com uma aba de dicas de alimentação saudável.
## 2. Casos de Uso

### 2.1 Caso de Uso I: Cadastrar Cliente
  - **Nível:** Administrador ou Cliente
  - **Atores primários:** Administrador e Cliente, 
  - **Interessados:**
    - **Administrador:** Efetuação de cadastro a fim de acessar o sistema.
    - **Cliente:** Efetuação de cadastro a fim de acessar o sistema.
  - **Pré-condições:** Acesso à Internet.
  - **Garantias de sucesso:** Clientes devidamente adicionado ao banco de dados. 
  - **Cenário de sucesso principal:**
	1. Cliente acessa a página web;
	2. Cliente seleciona o link Cadastrar ;
	3. Cliente preenche devidamente os campos do formulário de cadastro.
	4. Cliente confirma o cadastro
	5. Sistema confirma que o cadastro foi efetuado com sucesso.
  - **Extensões:** 
    - Passos 3 à 5: Campos preenchidos erroneamente:
      - Processo de cadastro é interrompido
      - Usuário recebe feedback relativos ao problema

### 2.2 Caso de Uso II: Cadastrar Produto
 - **Nível:** Administrador
 - **Atores primários:** Administrador
 - **Interessados:** 
	- **Administrador:** Efetuação de cadastro a fim de adicionar produtos ao banco de dados.
 - **Pré-condições:** Acesso à Internet.
 - **Garantias de sucesso:** Produtos devidamente adicionados ao banco de dados. 
 - **Cenário de sucesso principal:**
	 1. Administrador acessa a página web;
	 2. Administrador seleciona o link Cadastrar Produtos ;
	 3. Administrador preenche devidamente os campos do formulário de cadastro.
	 4. Administrador confirma o cadastro
	 5. Sistema confirma que o cadastro foi efetuado com sucesso.
 - **Extensões:** Passos 3 à 5 _ Campos preenchidos erroneamente:
	 a. Processo de cadastro é interrompido
	 b. Administrador  recebe feedback relativos ao problema.

### 2.3 Caso de Uso III: Editar Cliente
 - **Nível:** Administrador ou Cliente
 - **Atores primários:** Cliente
 - **Interessados:** 
  - **Cliente:** Realizar alterações em campos editáveis após cadastro.
 - **Pré-condições:** Acesso à Internet. Usuário autenticado.
 - **Garantias de sucesso:**
  - Campo devidamente alterado no banco de dados. 
  - Atualização do valor do campo exibido no sistema.
 - **Cenário de sucesso principal:**
    1. Cliente acessa a página web;
    2. Cliente seleciona o link Fazer Login;
    3. Cliente realiza o processo de autenticação;
    4. Cliente acessa seu Perfil;
    5. Cliente seleciona modifica o campo desejado;
    6. Cliente confirma a edição;
    7. Perfil do cliente é atualizado;
  - **Extensões:** 
    - Passo 3 _ Usuário ou senha inválidos:
      a. Processo de login é interrompido;
      b. Erro é notificado ao usuário;
      c. Dados são solicitados novamente;
    - Passos 5-6 _ Campos preenchidos erroneamente:
      a. Processo de edição é interrompido.
      b. Usuário recebe feedback relativos ao problema


