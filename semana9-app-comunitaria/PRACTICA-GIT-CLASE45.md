# Práctica Git - Clase 45

## Objetivo

Practicar ramas, stash, merge fast-forward, merge no-fast-forward y resolución de conflictos.

## Conceptos

- Rama:en Git es una línea de tiempo o bifurcación independiente del proyecto que te permite desarrollar nuevas funciones, corregir errores o hacer pruebas de código de forma aislada sin alterar la versión principal y estable de la aplicación.

- Commit:en Git es una captura de pantalla instantánea (snapshot) que guarda el estado exacto de tus archivos en un momento específico, actuando como un punto de control en la historia del proyecto al que siempre puedes regresar.

- Merge:en Git es el proceso de fusionar dos ramas independientes para integrar los cambios y el historial de una rama secundaria (como una nueva función) dentro de una rama principal (como main o master).

- Stash:Un stash en Git es un casillero temporal que te permite guardar de forma segura tus cambios locales no guardados para dejar tu espacio de trabajo limpio, permitiéndote cambiar de rama rápidamente sin perder tu progreso.

- Fast-forward:Un Fast-forward es un tipo de merge en Git que ocurre cuando la rama receptora no tiene cambios nuevos; en lugar de crear un commit de fusión, Git simplemente "adelanta" la punta de la rama hasta alcanzar el último commit de la rama secundaria.

- No-fast-forward:Un No-fast-forward (git merge --no-ff) es un tipo de fusión que obliga a Git a crear siempre un nuevo commit de unión (merge commit), manteniendo intacto el historial visual y la existencia separada de la rama que se integró.

- Conflicto:Un conflicto en Git ocurre cuando dos personas (o ramas) modifican la misma línea de código en un archivo de formas distintas y Git no puede decidir automáticamente cuál versión conservar, requiriendo que un humano elija la correcta de forma manual.

## Nota temporal

Esta nota todavía no está lista para commit.
## Mensaje de cierre

Desde tecnología y comunicaciones, la Semana 9 demuestra que levantar, proteger, diagnosticar, documentar y verificar una aplicación fortalece el proyecto y aumenta la confianza comunitaria.