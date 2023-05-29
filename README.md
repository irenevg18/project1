> Proyecto 1
**Actividad 7**

# Mini-proyecto de maquetación #

![imagen_de_portada](./src/img/readme-image.jpg)

En esta actividad practicaremos todo lo que hemos visto hasta ahora con tal de crear nuestra primera maquetación web.


## Objetivos ##

- Trabajar en un archivo **HTML** con sintaxis válida. (Solo un body, un head, ...)
- Utilizar correctamente los elementos HTML: h1-h6, button, a, nav, ul, li,...
- Hacer buen uso del **HTML semántico**.
- Replicar lo mejor posible el diseño escogido en la *medida de escritorio*.
- Utilizar **flexbox** y **grid** cuando sea necesario.
- Subir nuestra versión a [GitHub](https://github.com/)



---

### **Iniciamos la actividad** ###

1. Entrar en la carpeta donde vamos a ubicar la actividad:
    1. Abre la **terminal**.
    2. Con los comandos `cd` y `cd ..` navegamos por nuestro ordenador hasta llegar a la dirección dónde queremos ubicar la actividad.

2. Abrir en enlace de la actividad en el navegador.
3. Clonar la actividad:
    1. Copiamos el link *https* del botón *Clone* de nuestro **Github**.
    2. Vamos a la **terminal** y, dentro de la carpeta donde queremos ubicar la actividad, escribimos el comando `git clone + (pegamos el link que habíamos copiado)`.

4. Abrir la actividad en el **Visual Studio Code**
    1. Entramos dentro de la carpeta que se ha generado con el comando `git clone`, haciendo `cd + (el nombre de la carpeta clonada)`.
    2. Dentro de la carpeta, escribimos el comando `code .` para abrir esta carpeta en el **VSC**.



---


#### :raised_hand::warning: Antes de empezar :point_down: ####

Para utilizar **Tailwind** en nuestro proyecto tendremos que seguir los siguientes pasos:

1. Abrir la carpeta del repositorio en la **terminal**.

2. Ejecutar el siguiente comando: `npm install`.

3. Una vez terminen de instalarse las dependencias, ejecutamos este otro comando: `npm start`.

4. Veremos que nuestra terminal queda inutilizada compilando, así que tendremos que abir otra para ejecutar los [comandos de guardado](#mientras-trabajamos-en-la-actividad)

5. No debemos cerrar la terminal compiladora hasta que queramos pararla. Para ello, utilizamos el comando: `ctrl + c`.

---

### :point_right: **Ejercicio** ###

- Trabajaremos el archivo **index.html**.
- **No es obligatorio usar tailwind**.
- Si nos sentimos más cómodos usando directamente css:
    - Crearemos un documento styles.css y lo vincularemos al archivo **index.html** mediante la etiqueta **< link >** en la parte del **< head >**.
- Podemos escoger una de las siguientes propuestas o replicar una página que nos guste. (consúltame antes).

#### Propuestas ####

1. [Minimal portfolio 1](https://www.figma.com/file/6wwvT2WCdiFJorQQdPM3xd/Minimal-Portfolio-(Community)?type=design&node-id=0-1&t=pnObDcihv8CpZgRf-0)

2. [Minimal portfolio 2](https://www.figma.com/file/fWKEGpBEZdbrrfRmcyYict/Free-Minimal-Portfolio-Website-UI-(Community)?type=design&node-id=0-1&t=QKjrusvQ94jjGSWD-0)

3. [Biko landing page](https://www.figma.com/file/hATWD1oihPfrqQxHVUSu1A/Biko---Startup-Landing-Page-Template-(Community)?type=design&node-id=0-1&t=xpkSbcGiFNpNraaD-0)

4. [PF eventos](https://www.figma.com/file/aIduiOSkn6b0nq1M9pFv0O/Website-desing-(Community)?type=design&node-id=0-1&t=leLDyY65AXdrHNNL-0)

5. [Cosmetic store](https://www.figma.com/file/tb1W9EL8jXmqQru1LLu8G7/Miralou-Four---Cosmetic-Store-eCommerce-Theme-(Community)?type=design&node-id=2-2&t=OMKOOszIcvdHTlnJ-0)

6. [Product landing page](https://www.figma.com/file/n8PrT2vVxExl5ifvQEz1K5/Product-Landing-Page-(Community)?type=design&node-id=1-1366&t=sp1Yznlm3mTsl80N-0)

7. [Personal portfolio](https://www.figma.com/file/aTHEjq0UfirHcB1Fv9EvBl/Personal-Portfolio-Website-Template-(Community)?type=design)

8. [Minimal portfolio 3](https://www.figma.com/file/qbKgp8yiLtlzceBYU1FyGb/Minimal%2C-One-Page-Portfolio-Template-(Community)?type=design&node-id=0-1&t=Z1hnIr8vjvicXsKk-0)


9. [Portfolio template](https://www.figma.com/file/M15URwQZNO0vLmDQfyRdXM/Arnau-Ros-%E2%80%A2-Portfolio-Template-(Community)?type=design&node-id=0-1&t=bYDs1KErUJU7urLM-0)


### **Mientras trabajamos en la actividad** ###

Mientras trabajamos en la actividad es muy importante ir guardando los cambios que vamos haciendo. Este **proceso de guardado** será el siguiente: 

1. El clásico `ctrl + s` o `cmd + s` en nuestro archivo del **VSC**.
2. Abrimos la **terminal**, comprobamos que nos encontramos en la ruta correcta y escribimos los siguientes comandos:
    1. `git add .`
    2. `git commit -m "mensaje"`
    3. `git push`

3. Vamos al navegador y comprobamos que se ha hecho correctamente en nuestro **Github**.


---

### Recursos ###

- [Recurso 1](https://tailwindcss.com/docs/utility-first)

- [Instalación de Tailwind en un proyecto](https://tailwindcss.com/docs/installation)

- [Recurso 3](https://www.youtube.com/c/TailwindLabs)

