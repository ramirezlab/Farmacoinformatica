# Bienvenidos a su curso de farmacoinformática.

En este repositorio encontrarán el contenido e instrucciones para trabajar en las sesiones preparadas de acuerdo al programa del curso.

1. Para iniciar deben primero deben acceder a la máquina *Chernobyl* del RamirezLab.
   Debemos escoger un puerto para abrir la interfaz gráfica, para esto escogemos un número **único** de cuatro cifras (`####`) que se usará en adelante. El comando de acceso es:
   
   ```console
   ssh -L ####:localhost:#### invitado1@152.74.100.143
   ```
   
   (_recuerde cambiar `####` por el número escogido_)
   (passwd: **ramirezlab2022**):
2. Ahora, deben activar el ambiente de trabajo usando el comando
   
   ```console
   conda activate farmacoinformatica
   ```
   
   Este ambiente se encuentra en
   
   > *Farmacoinformatica-2022/00-Documentos/00-env/env.yml*
3. Luego, deben acceder a la carpeta `Farmacoinforamtica-2022` con el siguiente comando
   
   ```console
   cd Farmacoinforamtica-2022
   ```
4. Posteriormente, deben crear una carpeta con su apellido y nombre, sin usar espacios ni signos de puntuación, por ejemplo:
   
   ```console
   mkdir Ramirez_David
   ```
5. Luego accedan a la carpeta con el comando cd
   
   ```console
   cd Ramirez_David
   ```
6. Posteriormente, deben clonar este repositorio en su carpeta personal así:
   
   ```console
   git clone https://github.com/ramirezlab/Farmacoinformatica-2022.git
   ```
7. Ahora deben iniciar el servidor para poder trabajar con `Jupyter notebook`.
   
   ```console
   jupyter notebook --no-browser --port=####
   ```
   
   (_recuerde cambiar `####` por el número escogido_)
   
   Después de este comando, deben copiar el `token` para usarlo en los siguientes pasos.
   
   > Ejemplo:
   > 
   > Jupyter Notebook 6.4.11 is running at:
   > 
   > [I 17:51:58.257 NotebookApp] http://localhost:####/?token=0d47af2913ba0a8d65b8aa64933de2118299af2b918fc256

   
   El `token` en este caso sería:
   
   > **0d47af2913ba0a8d65b8aa64933de2118299af2b918fc256**
8. Lo siguiente es abrir cualquier navegador dentro del computador personal. Con esto abriremos la interfaz de jupyter mediante la tunelización. En el navegador:
   
   ```console
   localhost:####
   ```
   
   (_recuerde cambiar `####` por el número escogido_)
   
   Finalmente, la interfaz de jupyter nos pedirá un código de acceso llamado `token`, el cual se encuentra en el **numeral 7**.

De esta forma tendra activo `Juputer notebook` y podrá realizar las sesiones donde se emplee este servidor.

Ahora, en el navegador acceda a la carpeta creada al clonar este repositorio, y a la sesión de trabajo correspondiente.

Have Fun!!!

