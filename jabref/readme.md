
Step 1: Making layout files
There are two layout files that you need to define
First one is a begin layout file and second is an end/main layout file. Layout file means that the extension is .layout
You need to create a folder that store these two files, Name of the folder is whatever you want, let say jabref
Easy way is to download the templates of layouts from JabRef developer such as
https://github.com/JabRef/jabref/tree/main/src/main/resources/resource/layout/tablerefs
or from my github link
https://github.com/namkyodai/software-practice/tree/main/jabref
Example of a bib file is also available.
then save them under jabref	
 

Step 2: Modifying the content of the layout files
Modifying the content of the layout files is pretty easy, just open them with a text editor 
With begin layout file, you can define the header names or field names, let say of your CSV file.
With main layout file, you can define the format of how to export, rule of thumbs is that the order of fields is the same as the order in the begin layout file.
Another rule of thumbs is that in the main layout file, No Capital letter is allowed, all must be lower letter, and another importance is that better not to have any space between them, because if you have a space, the exported data will be wrapped inside a double quote “” which is ……. Annoying 
Example of layout files
Begin Layout
Entrytype,Groups,Title,Organization,Creationdate,Year,Month,Validity,Asset, Discipline, Stage, Category, Requirement, Must, Comment, Timestamp, Register,URL,File


Main/End Layout

"\entrytype","\groups","\title","\organization","\creationdate","\year","\month","\validity","\asset","\discipline","\stage","\category","\requirement","\must","\comment","\timestamp","\register","\url","\file"
Step 3: Define the Main Layout in the Preference of Jabref
 

Step 4: Exporting
 



















Assuming I have a library with several custom fields as you can see on the screen. Examples are columns Asset and Discipline




