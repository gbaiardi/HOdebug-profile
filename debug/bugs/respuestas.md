
    Correr el programa con un debugger, sin agregar flags de debug. ¿Tienen toda la información que requerían? NO
    ¿Qué pasa si ponen el flag de debug? optimiza modificando el código 
 
¿Qué flag de optimización es el mejor para debuggear? hay que compilar con el flag -O0 (por defecto tiene ciertas opt)
    Agreguen algún flag para que informe todos los warnings en la compilación, como -Wall. ¿Alguno les da alguna pista de por qué el programa se rompe? SI- add_array_dinamics da resultado 6 pero segmentation fault en main

add_array_segfault- violación de segmento 

