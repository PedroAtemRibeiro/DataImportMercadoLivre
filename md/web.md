3- We use the 'get' function to add the desired URL to Chrome.

![p2](https://user-images.githubusercontent.com/114637779/218186657-45ae6b66-809a-4398-b569-fca6a73e6a2f.png)


4- We use the 'Get_element' function and define "By.NAME()" as the type of identifier we will look for in the page's html. In this case, it is the search field of the Website that we will locate.
<br>


In this same function we call the function "Send_keys()" which is responsible for typing the desired content.

![p3](https://user-images.githubusercontent.com/114637779/218186686-1042ede9-2e35-4b83-b6c6-86773ccfc976.png)

5- We call the "get_element()" function again, but this time using the "By.PATH()" identifier, passing the parameter of the search button present in the page's html. And we finalize the function by calling the ".click()" function so that the search is carried out.

![p4](https://user-images.githubusercontent.com/114637779/218186719-318f7bfd-0c8e-42d9-8204-d537a430b70c.png)
