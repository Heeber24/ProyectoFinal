Proyecto Final: Security Suite

Tienen en sus manos la versión 1.0 funcional. Su trabajo será mejorar su funcionalidad y seguridad.

Requerimientos Obligatorios:
    1.	Modo sigilo: La contraseña maestra NO debe verse en la consola al escribirse. 
    2.	Persistencia universal: El archivo boveda.dat debe crearse siempre en la carpeta raíz del proyecto, sin importar desde dónde se ejecute el comando en la terminal.
    3.	Política de Contraseñas: Impedir que se creen bóvedas con contraseñas débiles (Mínimo 8 caracteres ).}
        •	Situación Actual: El sistema acepta "123" o "a" como contraseña maestra. Eso en ciberseguridad es un pecado.
        •	La Misión: Implementar una validación de fortaleza.
            o	Mínimo 8 caracteres.
            o	Al menos una mayúscula.
            o	Al menos un número.

  5.	Cambiar contraseña maestra. El sistema deberá tener la capacidad de poder realizar la modificación de la contraseña maestra considerando la regla de políticas de contraseñas.
  4.	Buscador Inteligente. Dentro del apartado de secretos existe una opción que se llama buscar secretos. El objetivo será mejorar el metodo de búsqueda en donde las palabras buscadas ya no deberán ser exactamente iguales.
  5.	Implementar metodo de actualizar. En el caso del gestor de contraseñas, estas podrán ser modificadas. Esto aplica únicamente para el gestor de contraseñas.
  6.	Crear una bitácora de registro de eventos. El objetivo será crear un archivo de texto plano (audit.log) que registre cada acción con fecha y hora.
      •	Ejemplo: [2025-11-20 10:00:00] INFO: Se agregó un secreto 'Gmail'.
      •	Ejemplo: [2025-11-20 10:05:00] WARN: Intento de descifrado fallido.
