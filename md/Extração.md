Definindo a Variavel que irá percorrer toda a lista de produto na pagina html.
![p5](https://user-images.githubusercontent.com/114637779/218190224-e60360dc-4431-4385-9356-919bc73ab34e.png)

Dentro do laço de repetição for, em cada execução é extraído os conteudos de: 


-  Nome do produto(Através do identificador CLASS_NAME)
-  Valor inteiro(Através do identificador CLASS_NAME)
-  Valor flutuante(Através do identificador CLASS_NAME)
-  Url produto(Através do identificador TAG_NAME)

![p6](https://user-images.githubusercontent.com/114637779/218190276-516ab502-608c-4184-b8d9-488be4853e40.png)

<br>
Em seguida, esses elementos sao salvos em variáveis.


Obs: é adicionado o tratamento de erro "Try/Except" na variavel de valor flutuante, onde a variável só é atribuida ao valor, se cumprir a condição de ser diferente de 0.
