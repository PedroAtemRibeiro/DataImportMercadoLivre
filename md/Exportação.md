
To OS control and manipulate files in excel we will use the openpyxl and OS libraries.


![p7](https://user-images.githubusercontent.com/114637779/218331477-29012dbb-2484-4e65-affd-9d3abd859da6.png)




 Assigning a specific worksheet from an xlsx file in the computer directory to a variable in the code.


![p9](https://user-images.githubusercontent.com/114637779/218331487-3532bd71-2f27-4c03-abd9-71bd2d67525a.png)




Within the loop of repeating the data extraction, we access the worksheet content at each execution.

![depois9](https://user-images.githubusercontent.com/114637779/218331496-5d870539-3225-42d6-98fc-781c38e29fda.png)




The row variable receives the number of the first empty row in the worksheet. And we create the column variables with the value of the coordinates of A, B and C.


![p8](https://user-images.githubusercontent.com/114637779/218331503-e1a87323-5848-46b3-bdc9-f14b5cd5ad39.png)




We add the values of the variables nomeProduto, Preço(formatado) e Url, to columns A, B and C in the line corresponding to the 'Linha' value of the time execution.

![p11](https://user-images.githubusercontent.com/114637779/218331513-ce385c1f-9265-497b-a80b-23fc94da331a.png)



Finally, we save the file with the name of the value assigned to the variable 'file_name_table' , and we tell the OS to open it.

![p12](https://user-images.githubusercontent.com/114637779/218331518-174a71c3-088b-414d-afc8-e872a32ef44f.png)

