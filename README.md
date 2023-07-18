<h1 align="center"> API para Controle de Usuários com Identity e .Net 6.0</h1>

## Descrição do Projeto
Esse projeto tem como objetivo concretizar os conhecimentos obtidos durante a minha formação feita na plataforna da Alura sobre criação de APIs Web no padrão REST com C#, Identity e Entity Framework e o LINQ.
Essa aplicação foi construida para fazer cadastros, autenticação e autorização de usuários de um sistema. Portando com ela você consegue cadastrar novos usuários, fazer login e ainda ela utiliza a autenticação via token.

## :hammer: Funcionalidades do projeto
- A API possibilita fazer o cadastro de um novo usuário por meio de um metodo POST e o objeto a ser passado deve conter o username, data de nascimento, uma senha e um confimação da senha. O username é unico para cada usuário então se tentar cadastrar um username que já exista ele retornará um erro, além disso a senha deve conter letra maiúscula, minúscula, número, caractere especial e no minímo 8 caracteres, segue abaixo um exemplo de cadastro:
<div align="center"> 
  
![cadastro](https://github.com/Joao-Marcelo-B/ControleDeUsuario-Api/assets/113398296/516d9fda-6809-4f2c-ae1a-fa8ab21051f1) 

</div>

- Após o cadastro o usuário é salvo no banco de dados e o próprio Identity grava a senha já criptografada e também gera o Id e entro outros dados de validação.
<div align="center>
  
![image](https://github.com/Joao-Marcelo-B/ControleDeUsuario-Api/assets/113398296/a0d3a851-f65f-4166-a540-31f6aaa2f386)
  
</div>

- Os usuários cadastrados podem efetuar o login e se suas credenciais estiverem corretas ele será autorizado e um token de acesso será gerado imeditamente. Segue o exemplo:
<div align="center"> 

<img src="https://github.com/Joao-Marcelo-B/ControleDeUsuario-Api/assets/113398296/2c45acd4-34c9-410e-b326-231d5f4e305a" />

</div>

- E por fim é possível ser feito uma requisição de acesso passando o token retornado após o login no "Auth" como um bearer token por meio de um método GET. Segue o exemplo:
<div align="center">

![image](https://github.com/Joao-Marcelo-B/ControleDeUsuario-Api/assets/113398296/49fcdcb9-940b-4746-bf74-ebdf32e8cf4c)

</div>



## 🖥️Tecnologias e Ferramentas

<img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-plain-wordmark.svg" /><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" /><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />

> Esse projeto foi construido com .Net 6.0

- Asp.Net Core
- Identity e Entity Framework
- JWT - Web Token
- LINQ
- Postman (aplicativo para realizar requisições para teste)

## Considerações Finais
Como havia dito inicialmente, esse projeto teve como objetivo a concretização dos conhecimetos obtidos ao longo da formação que realizei. Portanto, posso concluir que construindo esse projeto eu consegui exercitar os conhecimentos em APIs REST, protocolo HTTP, a linguagem de programação C# com Identity e Entity Framework e outras bibliotecas como AutoMapper para executar mapeamentos do banco de dados, além disso aprendi como fazer autorização e autenticação via Token com o JWT Bearer. Por fim fico satifesto com esse projeto, e animado para criação de novos projetos e obter mais conhecimeto sobre o desenvolvimento Back-end

## Contatos:

<div>
<a href="https://www.linkedin.com/in/joao-marcelo-b-narciso/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
<a href="https://instagram.com/joao_marcelo_79/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href = "mailto: joaomarcelobn157@hotmail.com "><img src="https://img.shields.io/badge/-Hotmail-%230077B5?style=for-the-badge&logo=microsoft-outlook&logoColor=white&link=mailto" target="_blank"></a>
</div>

## Desenvolvedores

[<img src="https://avatars.githubusercontent.com/u/113398296?v=4" width=115><br><sub>João Marcelo</sub>](https://github.com/Joao-Marcelo-B)
