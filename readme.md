[logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Bash
1. Using the echo command print in console "Hello World".
Para este pregunta, escrbí el comando (echo "Hello World"). Con ello, pude imprimir dicha frase.

2. Create a new directory called new_dir.
Para esta pregunta, utilicé el comando "mkdir" seguido del nombre del nuevo directorio "new_dir". Luego, ejecuté el comando "ls" para corroborar que se pudo crear dicho directorio.

3. Delete/Remove the directory new_dir.
Para borrar el nuevo directorio, utilicé el comando "rm -r" seguido del nombre del directorio.

4. Copy the file sed.txt from the lorem folder and paste it to the folder lorem-copy folder.
Para copiar el archivo sed.txt y pegarlo en el folder lorem-copy, tuve que ingresar a la carpeta lorem utilizando el comando "cd" y luego "ls" para ver los archivos que contenía la carpeta. Luego de ello copié el archivo utilizando el comando "CP" e indicando la carpeta de destino "../lorem-copy/". 

5. Copy the other two files from the lorem folder to lorem-copy folder in just one line using semicolon ";".
Utilicé el siguiente comando: cp at.txt at.txte lorem.txt ../lorem-copy/

6. Show the sed.txt file content from the lorem folder.
Utilicé el siguiente comando: cat sed.txt

7. Show the at.txt file and lorem.txt file contents from lorem folder.
Utilicé el comando: cat at.txt lorem.txt

8. Print the first 3 rows in sed.txt file from lorem-copy folder.
Utilicé el comando: head -n 3 sed.txt 

9. Print the last 3 rows in sed.txt file from lorem-copy folder.
Utilicé el comando: tail -n 3 sed.txt 

10. Add Homo homini lupus. at the end of sed.txt file in the lorem-copy folder.
Ingresé al texto del archivo utilziando "vim sed.txt". Luego escribí la palabra indicada y guardé/salí utilizando ":x!"

11. Print the last 3 rows in sed.txt file from lorem-copy folder. You should see Homo homini lupus.. 
Utilicé el comando: tail -n 3 sed.txt y pude ver la palabra agregada "Homo homini lupus".

12. sed command is used to replace the text in a file. Use the sed command to replace all occurances of et with ET in the file at.txt file present in the folder lorem. You can use the following link to refer to sed commands [https://www.linode.com/docs/guides/manipulate-text-from-the-command-line-with-sed/] Check the contents of the sed.txt file using cat command.
Utilicé el comando: sed "s/et/ET/g" at.txt

13. Find who is the system user.
Utilicé el comando: whoami


14. Find the current path of the directory you are in.
Utilicé el comando: pwd

15. List all files with the extension .txt in lorem folder.
Utilicé el comando: ls *.txt

16. Count the rows in sed.txt file from lorem folder. Look concatenate cat and wc with the pipe |.
Utilicé el comando: cat sed.txt | wc -l


17. Count the files which start with lorem in all directories.
Utilicé: ls lorem*
