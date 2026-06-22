# Bitácora de cierre - Semana 9 - Clase 45

## Datos generales

Nombre: LEIDER DAVID RAMOS CARO
Fecha:21/06/2026
Entorno: GitHub Codespaces
Rama de trabajo: clase-45-cierre-git-integrador

## 1. Verificación de aplicación

Comando usado para levantar la aplicación:npm start

Respuesta de /estado: 
App Comunitaria Semana 9

Aplicación activa.

Clase 42 - Seguridad operativa aplicada

Respuesta de /diagnostico: 
"entorno":"development","telegramConfigurado":true,"nota":"Esta ruta es de práctica.

Respuesta de /api/info:
"programa":"Capacitación en Democracia y Tecnología","alias":"Programadores para la Paz","semana"                                          :9,"clase":42,"tema":"Seguridad operativa aplicada"

## 2. Variables de entorno

¿Qué variables se usaron?
process.env, doten.

¿Por qué .env no debe subirse?
Porque contiene tokens, claves, usuarios y email

## 3. Seguridad operativa

¿Qué medidas de seguridad se aplicaron durante la semana?
como medidas de seguridad hicimos, .gitignore, gitkeet

## 4. Diagnóstico

¿Qué error simulado se trabajó durante la semana?
modificando archivos, como el de comunicasiones, mejora entre otras.
¿Cómo se corrigió?
con comandos como ff. no ff
## 5. Documentación

¿Qué documento explica el procedimiento de despliegue?

## 6. Git

¿Qué aprendí sobre ramas?
que las ramas son bifurcaciones independientes que aíslan el código para probar funciones sin romper la versión estable (main). Practicaste cómo crearlas, moverte entre ellas y unirlas mediante merges, manejando el flujo Fast-forward o forzando un historial claro con No-fast-forward, además de resolver manualmente los conflictos cuando dos líneas chocan.

¿Qué aprendí sobre stash?
ue el stash es un salvavidas temporal para guardar tus cambios inconclusos en un "casillero" oculto, permitiéndote limpiar tu espacio de trabajo para cambiar de rama urgentemente sin perder ni comprometer tu progreso.

¿Qué aprendí sobre merge fast-forward?
que el Fast-forward ocurre cuando la rama principal no tiene cambios nuevos, por lo que Git simplemente "adelanta" la punta de la rama hasta el último commit de la secundaria de forma lineal y sin crear un commit de fusión extra.

¿Qué aprendí sobre merge no-fast-forward?
que un No-fast-forward (--no-ff) obliga a Git a crear siempre un commit de fusión, lo que deja un rastro visual claro de que los cambios se desarrollaron en una rama independiente antes de unirse a la principal.

¿Qué aprendí sobre conflictos?
que los conflictos surgen cuando Git encuentra cambios contradictorios en la misma línea de un archivo y se detiene, exigiéndote decidir manualmente qué versión conservar antes de poder completar la fusión de las ramas.

## 7. Reflexión final

¿Qué fue lo más importante de la Semana 9?
Lo más importante de todo esto no son los comandos, sino la tranquilidad y el orden que te dan al trabajar. Entender Git te quita el miedo a equivocarte: sabes que puedes experimentar en una rama sin romper lo que ya funciona, guardar ideas a medias en el stash si surge una urgencia, y proteger los datos sensibles de tu comunidad usando variables de entorno.

Para aplicarlo en tu día a día, imagínalo como un escudo de seguridad: antes de tocar código importante, abre una rama nueva; documenta tus avances con commits claros; y si al unir el código aparece un conflicto, no te asustes, es solo Git pidiéndote una decisión humana. Al final, se trata de programar con la certeza de que tu proyecto está bajo control y tu historial cuenta una historia limpia.