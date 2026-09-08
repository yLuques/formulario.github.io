Formulário de Inscrição — Mostra de Tecnologia e Inovação

Informações do aluno

Aluno: João Renato Luques Comin

Objetivo do projeto

Este projeto foi desenvolvido como parte da atividade prática sobre **Formulários HTML com Bootstrap**.

O objetivo é criar uma página web contendo um formulário de inscrição para uma **Mostra de Tecnologia e Inovação**, utilizando diferentes tipos de campos disponíveis no HTML, validações nativas e componentes do framework Bootstrap.

O formulário possui caráter **demonstrativo**, não realizando armazenamento das informações em banco de dados.

A página foi organizada em diferentes seções para facilitar o preenchimento e melhorar a experiência do usuário.

---

Tecnologias utilizadas

* **HTML5** — Estrutura e criação dos campos do formulário.
* **Bootstrap 5.3.8** — Organização, responsividade e estilização dos componentes.
* **GitHub** — Versionamento e armazenamento do projeto.
* **GitHub Pages** — Publicação da página na internet.

---

Estrutura do projeto

text
formulario-bootstrap/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── img/
    └── enviar.jpg




Estrutura do formulário

O formulário foi dividido em diferentes seções:

Identificação do participante

Nesta seção são solicitadas informações básicas do participante, como:

* Nome;
* E-mail;
* Telefone;
* Senha demonstrativa;
* Idade;
* Arquivo para identificação;
* Curso;
* Opção de gênero;
* Motivo do preenchimento do formulário.

Dados de contato

São disponibilizados campos para informar os principais meios de contato e redes profissionais:

* GitHub;
* LinkedIn;
* Instagram.

Os campos de redes sociais utilizam o tipo `url`, permitindo a inserção de endereços de páginas da internet.

Formação e experiências

Nesta parte do formulário são coletadas informações relacionadas à formação acadêmica e experiência profissional:

* Ensino médio;
* Ensino superior;
* Experiência profissional.

Datas e disponibilidades

São utilizados diferentes tipos de campos relacionados a datas e horários:

* Data;
* Mês;
* Semana;
* Hora;
* Data e hora.

Esses campos permitem demonstrar as diferentes possibilidades de entrada de datas e horários disponíveis no HTML5.

Preferências

Nesta seção são utilizadas opções para representar preferências do participante:

* Escolha de uma cor;
* Controle deslizante (`range`);
* Opções utilizando `checkbox`.

Informações sobre o projeto

O participante pode informar:

* Tipo do projeto;
* Arquivo PDF para revisão;
* Descrição do projeto.

Para o tipo de projeto foi utilizado um `datalist`, permitindo apresentar sugestões como:

* Ambiental;
* Pessoal;
* Tecnológico;
* Científico;
* Musical.

Botões de ação

Ao final do formulário existem diferentes botões para demonstrar ações possíveis:

* Envio do formulário;
* Limpeza dos campos;
* Nova tentativa.



# 🔎 Investigação sobre os tipos de input

Durante o desenvolvimento foram utilizados diferentes tipos de `input` disponíveis no HTML5.

 Tipo             | Função                                                                       
 ----------------  ---------------------------------------------------------------------------- 
 `text`            Permite inserir textos simples, como nome e instituição.                     
 `email`          Utilizado para endereços de e-mail e realiza validação básica do formato.    
 `password`        Permite inserir informações ocultando os caracteres digitados.               
 `number`          Permite inserir valores numéricos.                                           
 `tel`             Indicado para números de telefone.                                           
 `url`             Utilizado para endereços de sites e redes sociais.                           
 `search`          Campo destinado a pesquisas e buscas.                                        
 `date`           Permite selecionar uma data.                                                 
 `month`          Permite selecionar mês e ano.                                                
 `week`            Permite selecionar uma semana do ano.                                       
 `time`            Permite selecionar um horário.                                               
 `datetime-local`  Permite selecionar data e horário.                                           
 `color`          Permite selecionar uma cor.                                                  
 `range`           Cria um controle deslizante para selecionar um valor dentro de um intervalo. 
 `file`            Permite selecionar arquivos do computador.                                   
 `checkbox`        Permite selecionar uma ou várias opções.                                     
 `radio`           Permite escolher uma opção dentro de um grupo.                               
 `hidden`          Armazena um valor que não é exibido diretamente para o usuário.              
 `submit`          Envia o formulário.                                                          
 `reset`          | Limpa os valores preenchidos no formulário.                                  
 `button`         | Cria um botão para ações personalizadas.                                     
 `image`          | Utiliza uma imagem como botão de envio do formulário.                        

Outros elementos HTML utilizados

Além dos diferentes tipos de `input`, o projeto utiliza outros elementos importantes para construção de formulários.

### `select`

Utilizado para criar uma lista de opções, como os cursos disponíveis.

### `textarea`

Utilizado para permitir que o usuário escreva textos maiores, como:

* Motivo do formulário;
* Experiência profissional;
* Descrição do projeto.

### `datalist`

Utilizado para fornecer sugestões ao usuário enquanto ele digita o tipo do projeto.

### `fieldset`

Utilizado para agrupar campos relacionados dentro do formulário.

### `legend`

Utilizado para criar o título de cada grupo de campos.

---

Validações utilizadas

O formulário utiliza recursos de validação nativa do HTML5.

Entre eles estão:

* `required` — define campos que precisam ser preenchidos;
* `minlength` — define o número mínimo de caracteres;
* `maxlength` — define o número máximo de caracteres;
* `min` — define um valor numérico mínimo;
* `max` — define um valor numérico máximo;
* `step` — define o intervalo entre valores numéricos;
* `pattern` — permite definir um formato específico para determinados campos;
* `placeholder` — apresenta uma dica dentro do campo;
* `accept` — define os formatos de arquivo aceitos.

O campo de senha contém um aviso para que o usuário **não utilize sua senha real**, pois o formulário possui finalidade exclusivamente acadêmica e demonstrativa.

Respostas da investigação

### Por que utilizar `type="email"` em vez de `type="text"`?

O tipo `email` é específico para endereços de e-mail e permite que o navegador realize uma validação básica do formato informado. Já o tipo `text` aceita qualquer conteúdo textual.

### Qual a diferença entre `radio` e `checkbox`?

O `radio` normalmente é utilizado quando o usuário deve escolher **apenas uma opção** dentro de um grupo.

O `checkbox` permite selecionar **uma ou várias opções simultaneamente**.

### Para que serve o atributo `required`?

O atributo `required` determina que o campo precisa ser preenchido antes que o formulário possa ser enviado.

### Para que serve o `accept` em um campo `file`?

O atributo `accept` permite indicar quais tipos de arquivos devem ser aceitos pelo campo. Neste projeto, ele é utilizado para permitir arquivos no formato PDF.

### Qual a função do Bootstrap?

O Bootstrap é um framework que fornece classes e componentes prontos para facilitar a criação de páginas web organizadas, responsivas e visualmente padronizadas.


Publicação

O projeto pode ser publicado utilizando o **GitHub Pages**, permitindo que o formulário seja acessado diretamente pelo navegador.

**Link do projeto publicado:**

> 🔗 [COLOCAR AQUI O LINK DO GITHUB PAGES]


Autor

**João Renato Luques Comin**


