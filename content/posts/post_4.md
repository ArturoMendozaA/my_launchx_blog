---
title: "Contribution activity"
date: 2022-04-09
description: 'email y nombre de usuario'
---

# No aparecen mis contribuciones
A muchas personas les ocurre esto y aunque puede ser que sea un asunto de que si es un fork o no, para mi el problema fue que tenía otro nombre.

Pueden revisar el nombre que tienen registrado en su git desde la terminal con el comando ``` $ git config user.name ```, para el mail ```$ git config user.email```

Y podemos modificarlos con los siguintes comandos:

```$ git config --global user.name "nombre de tu usuario de git"```

```$ git config user.email "tu email" ```

Ahora lo importante es que en el nombre tengan el mismo email que sus usuario de github y para que apareciera mi imagen de usuario también tenia que ser el mismo nombre de usuario que en git,  mi caso: ArturoMendozaA

Esto lo hice en la terminal, pero me di cuenta de que las contribuciones desde VSCode aparecian sin mi imagen de ususario, así que desde la termina dentro de VSCode volví a introducir mi email con el mismo código ```$ git config user.email "tu email" ```

y con esso ya parecen mis contribuciones (pero no las del fork :confused: ) 

![Imagen de la terminal](images/uno.png)

![Imagen del nombre de usuario en github](images/tres.png)

![Test Image](/uno.png)
<img src = "/uno.png">

![Test Image](/tres.png)
<img src = "/tres.png">

