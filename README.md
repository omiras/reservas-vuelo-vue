# Todos a bordo con Vue

1. Utiliza adecuadamente la directiva v-for para renderizar tantas reservas de vuelo como elementos hay en el array _flightReservations_ ¡Cuidado! El tipo de dato que alberga este array es un array de objetos.

   1. Primero, utiliza v-for adecuadamente para renderizar tantos `<article>` como elementos hay en el array.
   2. Luego, UNO A UNO, identifica cada uno de los campos que debes renderizar en el HTML

2. Fíjate en la demo que cuando la categoría es "First Class", esta aparece con la clase CSS .first-class aplicada
3. Debes renderizar Vuelo cancelado o Vuelo confirmado en función de si el vuelo está cancelado o no. En princpio, solo hay un vuelo cancelado de todos los vuelos presentes

## BONUS

1. Crea un `<select>` que permita filtrar todos los vuelos por categoría. Recomendación: Crea una computed property e itera con v-for sobre ella, en vez de sobre la variable flightReservations
