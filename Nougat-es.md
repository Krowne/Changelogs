# Nougat para KMod FWA

Debido a la continua insistencia de la gente para que adapte KMod FWA para Nougat y superior, he decidido redactar este artículo.

Los motivos por los cuales no funciona el módulo, es porque Nougat a cambiado los permisos para usar MODE_WORLD_READABLE, que se utiliza para leer las preferences desde Xposed, y ahora no está permitido su uso, por lo tanto, tengo que usar MODE_PRIVATE, el cual no funciona con Xposed. Así que, como tengo que cambiar la manera en que Xposed lee todos los valores de las variables asignadas en KMod FWA, tengo que crear el código para ello y adaptarlo, el cual es mucho trabajo. 

Además actualmente Xposed para Nougat, no es una versión final de robo89 y tiene bastantes bugs, no voy a crear el código para algo que ya he probado y no funciona con recursos. Así que hasta que robo89 no publique Xposed para Nougat de forma estable, no empezaré a trabajar en el soporte para Nougat. Sobretodo, porque estoy trabajando en otro proyecto que posiblemente sustituya a KMod FWA, el cual irá preparado para trabajar sobre Nougat.

Así que por favor, paciencia, porque si todos insistís con lo mismo, lo único que vais a conseguir, es que se me quiten las ganas de trabajar en ello.

Un saludo, y gracias a todos los que apoyan mi trabajo.

Krowne.
