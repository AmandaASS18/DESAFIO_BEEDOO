## DESAFIO_BEEDOO
### Amanda Aparecida Santana dos Santos 
- Email: amanda.aass@outlook.com
- [LinkedIn](https://www.linkedin.com/in/amandasantanas/)  

### Links Úteis  
- [Casos de Teste](https://docs.google.com/document/d/1_hSN-6fG4ONkWjynif7VXEB24rZ3Jq7ASyOrIKc9HUk/edit?usp=sharing)  
- [Evidências](https://drive.google.com/drive/folders/1zUseBP5PcY1lIR2EmQR5NyYQVj_ZdN-m?usp=drive_link)  
- [Decisões tomadas]()  

### User Story 001 - Lista de Cursos Cadastrados

[^1]: **Eu** como Analista de Qualidade  
**Quero** que seja desenvolvido uma lista de cursos cadastrados na plataforma Beedoo  
**Para** que o usuário ao acessar a plataforma possa visualizar os cursos disponíveis  

**Critérios de aceite:**  
- Lista de Cursos cadastrados;
- **Filtro**;
- Campo de **pesquisa**;
- Botão **Excluir**;
- Botão **Editar**;
- Botão **Inscreva-se**;    
  
**Regras de Negócio:**     
- Ao acessar o Formulário de Inscrição Beedoo, o usuário deverá visualizar a lista de cursos de forma ordenada, **sendo um curso por linha, contendo: imagem, nome do curso e descrição**;  
- Ao clicar em **Filtro** deverá possibilitar o usuário pesquisar o curso desejado por **ordem alfábetica, modalidade (presencial ou online), e por nome**;  
- Ao clicar no **campo de pesquisa** deverá possibilitar o usuário pesquisar o curso por nome, digitando as 3 primeiras letras;
- Ao clicar no botão **Excluir**, deverá apresentar tela de confirmação de exclusão **"Você deseja excluir esse curso?"** com as opções **"sim"** e **"não"**;  
- Ao clicar no Botão **Editar**, deverá apresentar a a ficha de cadastro do curso escolhido, com os campos abertos para edição;  
- Ao clicar em **Inscreva-se**, deverá direcionar o usuário para a ficha de dados do aluno;  


### User Story 002 - Cadastrar Curso

**Eu** como Analista de Qualidade    
**Quero** que seja desenvolvido uma funcionalidade de Cadastrar Cursos na plataforma Beedoo    
**Para** que o usuário ao acessar a plataforma possa cadastrar novos cursos quando desejar.  

**Critérios de aceite:**  
- Campo input **Nome do Curso**;
- Campo input **Descrição do Curso**;
- Campo input **Instrutor**;
- Campo input **URL da Imagem de Capa**;
- Campo Date Picker **Data de Início**;
- Campo Date Picker **Data de Fim**;
- Campo input de número **Número de vagas**;
- Campo Select box **Tipo de Curso**;
- Botão **Cadastrar Curso**.  
  
**Regras de Negócio:**     
- Ao acessar o menu **Cadastrar Curso**, o usuário deverá visualizar a Ficha de Cadastro do Curso com os campos: **Nome do Curso, Descrição do Curso, Instrutor, URL da Imagem de Capa, Data de início, Data de Fim, Número de vagas e Tipo de Curso**;
- Todos os campos do formulário de cadastro **são obrigatórios**;
- Caso o usuário não preencha um dos campos e clique em **"Cadastrar Curso"**, deverá apresentrar mensagem informando que os campos são obrigatórios;
- O campo **Nome do Curso** poderá ser preenchido apenas com Letras;  
- O campo **Descrição** poderá ser preenchido com letras, números e caracteres especiais;
- O campo **Instrutor** poderá ser preenchido apenas com Letras;  
- O campo **URL da Imagem de Capa** deverá ser preenchido com um link válido, **type="url"**;  
- Ao clicar em **Cadastrar Curso** após preencher todos os campos com dados válidos, deverá cadastrar o curso e apresentar mensagem de **"Cadastro realizado com sucesso"**;


