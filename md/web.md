3- Usamos  a função 'get' para adicionar a URL  desejada ao Chrome.

![p2](https://user-images.githubusercontent.com/114637779/218186657-45ae6b66-809a-4398-b569-fca6a73e6a2f.png)


4- Usamos a função 'Get_element' e definimos "By.NAME()" como tipo de identificador iremos procurar no html da pagina. Nesse caso, é o campo de busca do Website que iremos localizar.
<br>

  Nesta mesma função chamamos a função "Send_keys()" que é responsavel por digitar o conteúdo desejado.

![p3](https://user-images.githubusercontent.com/114637779/218186686-1042ede9-2e35-4b83-b6c6-86773ccfc976.png)

5- chamamos a função "get_element()" novamente, porem dessa vez  usando o identificador "By.PATH()", passando o parametro do botão de buscar presente no html da página. E finalizamos a função chamando a função ".click()" para que a busca seja feita.

![p4](https://user-images.githubusercontent.com/114637779/218186719-318f7bfd-0c8e-42d9-8204-d537a430b70c.png)
