<h1 align="center">
  📄 Validação de Formulário de Login
</h1>


## :rocket: Sobre o projeto
Este é um formulário simples desenvolvido em ReactJS apenas para estudo sobre a criação e validação de formulários.

A responsabilidade de lidar com eventos nos campos e o submit do formulário ficaram por conta do "formik", juntamente com seus componentes para criação de formulário e tratamento de erros.
Já o "Yup" ficou encarregado da validação dos campos do formulário, foi criado um schema de validação de cada campo informando quais validações eles devem ter.

Na página de Login o usuário deve informar os seguintes dados:
- E-mail;
- Senha.

Caso um dos campos esteja vazio ou preenchido com dados inválidos são exibidas na tela mensagens com os erros. 

No e-mail, caso ele não esteja preenchido em formato de e-mail, por exemplo sem o "@", é exibida a mensagem de erro.
Já na senha a mensagem de erro é exibida caso ela possua menos de 8 caracteres.



## :computer: Tecnologias usadas:

### ReactJS:

- `react, react-dom, react-scripts`: Para o acesso aos elementos HTML, a árvore de elementos e alguns scripts para a aplicação no ReactJS;
- `formik`: Para trabalhar com formulários;
- `yup`: Para validação dos campos.


## :bulb: Telas


![tela1](https://user-images.githubusercontent.com/23708544/89242147-37425380-d5d7-11ea-8f59-22748c3d7fdc.png)

![tela2](https://user-images.githubusercontent.com/23708544/89242148-37425380-d5d7-11ea-998e-9b9f3bbed0d0.png)

![tela3](https://user-images.githubusercontent.com/23708544/89242150-37daea00-d5d7-11ea-86a7-0a86ddfdf7cd.png)

![tela4](https://user-images.githubusercontent.com/23708544/89242151-38738080-d5d7-11ea-8d6e-8fad57034139.png)

![Captura de Tela (171)](https://user-images.githubusercontent.com/23708544/89242141-34dff980-d5d7-11ea-98b8-6e6b6cb96ee4.png)

