# generador-de-pdfs
Generador de pdfs a partir de un json con preguntas, examenes con hasta 10 preguntas randomizadas. La ventaja de esta solucion es no tener que hostearlo en ningun lado ya que es un solo archivo html que se puede correr en cualquier navegador. Es rapido de usar y de generar los archivos y permite editar el titulo y el subtitulo. El codigo es javascript en html asi que con ganas y un poquito de conocimiento se podria editar para cambiar tamaños de fuentes, disposiciones, etcetera.

# Uso

## Abrir el html
Descargar el archivo .html o crear un archivo .html en la computadora local y guardarlo con cualquier nombre y la extension de archivo .html

![image](https://github.com/Manuel1Aguilar/generador-de-pdfs/assets/34017787/cef737ef-b24b-44c0-af47-702bdd809560)

Al abrirlo utilizando un navegador se mostrara la pantalla en la que pueden elegir titulo, subtitulo, numero de preguntas por examen y numero de examenes a generar. Tambien esta el boton para cargar el archivo de preguntas que debe utilizar el generador para generar los examenes

![image](https://github.com/Manuel1Aguilar/generador-de-pdfs/assets/34017787/7e2cd8b6-97c5-430e-88cf-3bbce3dc2452)

En este repositorio hay un archivo de ejemplo de preguntas con el formato que debe tener para poder utilizarlo

![image](https://github.com/Manuel1Aguilar/generador-de-pdfs/assets/34017787/0f51f422-a07e-4ac2-a2d7-7d2c2aed941a)

El archivo generado se ve asi con una pagina por examen:
![image](https://github.com/Manuel1Aguilar/generador-de-pdfs/assets/34017787/02b29af7-f9f9-4605-8fbe-e1e6481c7e27)


### Consideraciones
Si es muy imposible trabajar editando un json se puede expandir la solucion para generar el json automaticamente o aceptar un csv que se pueda generar desde excel pero esta opcion me parecio lo suficientemente simple.
No funciona muy bien con preguntas o respuestas que ocupen mas de un renglon, pegarle una revisada a todos los examenes en caso de utilizarlo para asegurarse que no se sobreponen los textos.
