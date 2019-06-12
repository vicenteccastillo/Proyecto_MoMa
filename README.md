# Proyecto MoMa 

El presente trabajo tratará de poner en vigencia una de las principales reinvidicaciones que realizaron y que siguen ejerciendo el colectivo Guerrilla Girl.
## Introducción 
Este colectivo (https://www.guerrillagirls.com/) surgió en 1985 en respuesta a una exposición que se realizó en el MoMa, en la cual se presentó una exposición con los artistas mas importantes del siglo XX y no participaba ninguna mujer.

![alt text](mujeresmuseo.jpeg \"mujeres museo\")

Una de las reinvindicaciones por las cuales surgió y que perdura en la actualidad es el bajo número de mujeres artistas que se encuentran en los museos. En este trabajo se va a intentar verificar si las reinvindicación de que solamente un 5% de las artistas en el MoMa son mujeres y si esta lucha por parte de este colectivo ha tenido una influencia en el mundo de los museos de arte

## Desarrollo del trabajo 

Por ello en un primer momento tomaremos desde la base de datos del museo, los artistas y obras que se encuentran en su catálogo, en esto es bueno señalar que en exposición se suele tener un número de obras pero en los almacenes suele aumentar el número, por lo que en este caso se va a contar con todas las obras que tiene el museo, tanto si están en exposición como en los almacenes.

### Creación de los DataFrame, limpieza de los datos y unión de los mismos

Una vez creados los DataFrame, se procede a la limpieza de los mismos y se realiza un *merge* de los mismos mediante la variable ***Artist_ID***, con esta unión ya se crean las variables *Hombre, Mujer y Desconocido* con las que se realizará el posterior análisis 

### Primeros resultados 
Si analizamos el % de obras por el género del autor se puede apreciar como los hombres representan un 81,7%, 86,06% si sólo tomamos las obras en las cual se sabe el género del artista.
Este porcentaje es mejor que el 5% que manifestaban las Guerrilla Girls en 1985, pero sigue lejos de ser equiparable con la obra masculina, en este sentido también se tiene que tener en cuenta que la mujer también representa un porcentaje bajo de artistas que se consideran importantes.

Una vez obtenidos estos porcentajes se intentan ver quienes son los artistas según el género que mas representación tiene, asi también por nacionalidad

### ¿Tenían razón el movimiento Guerrilla Girl? 

Con los datos disponibles y gracias a que tenemos una variable llamada ***Acquisition_Datenew*** podemos conocer si los datos que indicaban eran ciertos o no.
Por ello se categoriza  la variable según tres tramos desde el año 0 hasta el 1925, este tramo es por si existe algún dato mal codificado, el segundo al cual llamaremos *preguerrilla* el cual se situa en obras desde 1925, año de la fundación del museo y 1985 y el siguiente grupo al cual llamaremos *postguerrilla* que se encuentra entre 1985 y la actualidad (2019)

Con estos datos podemos ver como el porcentaje de obras atribuidas a mujeres era de un 6,48% frente al 93,52, por lo que el dato que indicaban las Guerrilla Girls era bastante acertado y como en la etapa postguerrilla el porcentaje de obra que ha sido adquirido de mujer ha representado el 22,43%, por lo que se puede afirmar que este colectivo ha tenido una influencia dentro del museo.

## ¿ Es esto así en otros museos? 

Esta investigación sería interesante realizarla con datos de otros museos, pero estos no se obtienen tan fácilmente, los que si se han podido conseguir es los del museo de Harvard gracias a una descarga de los datos de la API
