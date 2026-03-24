
Define con tus palabras qué es un conflicto de merge y cuándo suele ocurrir.

es una pausa en el proceso de integración de código que ocurre cuando Git no puede resolver automáticamente las diferencias entre dos ramas

Explica el significado de cada marcador en un conflicto:

    <<<<<<< HEAD
    =======
    >>>>>>> nombre-de-la-rama
<<<<<<< HEAD inicia los cambios de tu rama actual
======= separa los cambios.
>>>>>>> nombre-de-la-rama finaliza los cambios de la otra rama. Debes editar el archivo para eliminar los marcadores y decidir qué código conservar


¿Qué buenas prácticas pueden ayudar a reducir conflictos en un equipo (tamaño de los commits, frecuencia de merge, comunicación, etc.)?

una buena practica seria hacer commits pequeños y frecuentes
