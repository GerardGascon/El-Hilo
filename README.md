# El Hilo: Interactive Edition

En un intento de evitar pagar la API de twitter vamos a hacer un proyecto open source colaborativo para convertir El Hilo(tm) en una história interactiva.

## Como colaborar

Estoy usando [ink](https://www.inklestudios.com/ink/) así que tendrás que usar esto si quieres colaborar

Descarga el código, añade los twits que sean y espera a que lo haga la siguiente persona :)

Cuando añadas tu código no te olvides de añadir tu nombre en los créditos.

## Como escribir

### Knottiers

Para escribir ramas del hilo(tm) hay que usar nodos siguiendo la nomenclatura `nombrePersonaNúmeroKnottier` por ejemplo: `aquiles1`, `eufrasio69`

```
=== nombre_knottier ===

contenido aquí
```

> Cada knottier de cada persona debería de ir en un archivo distinto para intentar mantener el código organizado.

### Opciones

Para hacerlo sencillo usamos el símbolo `+` seguido del nombre de la cuenta y luego lo enlazamos con su knottier usando `-> nombre_knottier`:

```
+ [NombreCuenta]
    -> nombreCuenta1
+ [NombreOtraCuenta]
    -> nombreOtraCuenta1
```

> Importante: Usarlos solo cuando se generen ramificaciones

### Saltos de línea

Para los saltos de línea hay que usar el tag `<br>`:

```
Aquiles: VALE<br>KINKY<br>SI ME PREGUNTAS
```

### Imágenes o vídeos

Las imágenes o vídeos se enlazaran mediante links en los tags, al final del twit se le añade un `#link`, las dobles barras cuentan como comentario, por lo que hay que escribirlas así: `\/\/`

```
Eufrasio: ...no te gusta el salmorejo...<br>Andaluz promedio leyendo esto:#https:\/\/pbs.twimg.com/media/GM6x3veXAAAmE93?format=jpg&name=360x360
```

### Finalizar

Cuando una rama termina hay que cerrarla usando un `END`

```
=== aquiles4 ===
Aquiles: #https:\/\/pbs.twimg.com/media/GM7SAihXcAApuY7?format=png&name=small
Eufrasio: QUE ME HAGAS ZOOM EN LA FOTO ESTA Q NO VEO
-> END
```

## Créditos

- [Geri](https://twitter.com/G_of_Geri)