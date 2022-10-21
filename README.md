# Bienvenidos a su curso de farmacoinformática.

En este repositorio encontrarán el contenido e instrucciones para trabajar en las sesiones preparadas de acuerdo al programa del curso.

1. Para iniciar deben primero acceder a la maquina *Chernobyl* del RamirezLab.
   Se debe escoger un puerto para abrir la interfaz gráfica, para esto se debe especificar un número de cuatro cifras (_####_) que usará en adelante
   Mediante la siguiente opción de comando (usando como passwd: **ramirezlab2022**):
   
   ```console
   ssh -L ####:localhost:#### invitado1@152.74.100.143
   ```
   _ recuerde cambiar #### por el número escogido.

2. Luego, deben acceder a la carpeta “Farmacoinforamtica-2022” con el siguiente comando
   
   ```console
   cd Farmacoinforamtica-2022
   ```

3. Posteriormente deben crear una carpeta con su apellido y nombre, sin usar espacios ni signos de puntuación, por ejemplo:
   
   ```console
   mkdir Ramirez_David
   ```

4. Luego accedan a la carpeta con el comando cd
   
   ```console
   cd Ramirez_David
   ```

5. Posteriormente deben clonar este repositorio en su carpeta personal así:
   
   ```console
   git clone https://github.com/ramirezlab/Farmacoinformatica-2022.git
   ```
6. Ahora se debe activar el ambiente de trabajo usando el comando:
   
   ```console
   conda activate farmacoinformatica
   ```
   
   Este ambiente se encuentra en
   
   > *Farmacoinformatica-2022/00-Documentos/00-env/env.yml*
   
7. Ahora debemos iniciar el servidor para poder trabajar con Jupyter notebook. Para poder abrir el cuaderno de jupyter, sin interferencia de otros usuarios que estén utilizando la cuenta de invitado simultáneamente, vamos a crear un túnel para abrir el cuaderno en nuestro navegador local. Para esto debemos definir el puerto, que serán 4 dígitos (**####**). Estos números deben diferir con los de otros usuarios, para no causar interferencia. Por ejemplo
   
   ```console
   jupyter notebook --no-browser --port=1234
   ```
   
   Despues de este comando, deben copiar el token para usarlo en los siguientes pasos.
    
   Lo siguiente es abrir cualquier navegador dentro del computador personal, especificando el puerto. Con esto abriremos la interfaz de jupyter mediante la tunelización. En el navegador:
   ```console
   **localhost:####**
   ```
   
   Finalmente, la interfaz de jupyter nos pedirá un código de acceso llamado “token”, el cual se encuentra en la primera terminal, donde activamos jupyter.
   
   Ejemplo:
   
   ```console
   Jupyter Notebook 6.4.11 is running at: 
   [I 17:51:58.257 NotebookApp] http://localhost:1234/?token=0d47af2913ba0a8d65b8aa64933de2118299af2b918fc256
   ```
   
   El token en este caso sería:
   
   > **0d47af2913ba0a8d65b8aa64933de2118299af2b918fc256**

De esta forma tendra activo Juputer notebook y podrá realizar las sesiones donde se emplee este servidor.

Ahora, en el navegador acceda a la carpeta creada al clonar este repositorio, y a la sesion de trabajo correspondiente.

Have Fun!!!

