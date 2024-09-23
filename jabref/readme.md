- **Step 1: Creating layout files**

There are two layout files that you need to define

First one is a begin layout file and second is an end/main layout file. Layout file means that the extension is .layout

You need to create a folder that store these two files, Name of the folder is whatever you want, let say jabref

Easy way is to download the templates of layouts from JabRef developer such as
https://github.com/JabRef/jabref/tree/main/src/main/resources/resource/layout/tablerefs

or from my github link
https://github.com/namkyodai/software-practice/tree/main/jabref

Example of a bib file is also available, then save them under jabref	
![Screenshot 2024-09-23 210718](https://github.com/user-attachments/assets/61a506f7-4c84-447b-bb42-25517741cf32)

- **Step 2: Modifying the content of the layout files**

Modifying the content of the layout files is pretty easy, just open them with a text editor 
With begin layout file, you can define the header names or field names, let say of your CSV file.
With main layout file, you can define the format of how to export, rule of thumbs is that the order of fields is the same as the order in the begin layout file.

Another rule of thumbs is that in the main layout file, No Capital letter is allowed, all must be lower letter, and another importance is that better not to have any space between them, because if you have a space, the exported data will be wrapped inside a double quote “” which is ……. Annoying 
Example of layout files

*Begin Layout*
Entrytype,Groups,Title,Organization,Creationdate,Year,Month,Validity,Asset, Discipline, Stage, Category, Requirement, Must, Comment, Timestamp, Register,URL,File

*Main/End Layout*
"\entrytype","\groups","\title","\organization","\creationdate","\year","\month","\validity","\asset","\discipline","\stage","\category","\requirement","\must","\comment","\timestamp","\register","\url","\file"

- **Step 3: Define the Main Layout in the Preference of Jabref**
![Picture1](https://github.com/user-attachments/assets/1d94928b-e6e1-42fb-ac6b-bf49e026cda4)

 - **Step 4: Exporting**
![Picture3](https://github.com/user-attachments/assets/c62c7902-e3dd-4502-a4e3-f09d1ee5d472)
