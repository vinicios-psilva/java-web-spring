<h1 align="center">Desenvovimento Java Web no Spring Boot</h1>



<p>Desenvolvimento de uma API REST com banco de dados, utilizando Java e Spring Boot</p>

<h2> Softwares utilizados </h2>
 <li>Eclipse IDE 2022
 <li>Spring Boot
 <li>Postman
 <li>brModelo

<h2>Visão geral do sistema</h2>
  Construir um pequeno sistema(API REST) de usuários e departamentos, com os seguintes casos de usos:
  <li>Buscar todos os usuários
   <li>Buscar usuarios pelo Id
    <li>Inserir um novo usuário

![relacional](https://user-images.githubusercontent.com/97298193/148815005-952c10f3-63fd-4319-a71f-17b4199d88d4.PNG)

tb_department
| id | name        |
|----|-------------|
| 1  | Gestão      |
| 2  | Informática |

tb_user
| id | name  | email           | id_department |
|----|-------|-----------------|---------------|
| 1  | Maria | maria@gmail.com | 1             |
| 2  | Bob   | bob@gmail.com   | 1             |
| 3  | Alex  | alex@gmail.com  | 2             |
| 4  | Ana   | ana@gmail.com   | 2             |
     

![department](https://user-images.githubusercontent.com/97298193/148825385-bdfe8f3e-bbc2-4127-9e7b-70aa5cdd7771.PNG)
![postman](https://user-images.githubusercontent.com/97298193/148825399-574d11b3-02f9-42f9-bda2-6214d9baa51c.PNG)
     
<h2>Códigos</h2>
     <p>Configuração utilizado no Maven</p>

![maven](https://user-images.githubusercontent.com/97298193/148828049-b877b3f7-0d99-418b-b21c-a540914435c4.PNG)
	    
<p>Configuração do Banco de Dados</p>

![bancoDeDados](https://user-images.githubusercontent.com/97298193/148828171-32621de5-1aec-4935-b00f-d4003f13d4f2.PNG)
	    
<p>Script SQL</p>
	    
![bancDeDado2](https://user-images.githubusercontent.com/97298193/148828278-87d2a1a6-c620-4c6d-a06f-5e6c72b28a0a.PNG)


