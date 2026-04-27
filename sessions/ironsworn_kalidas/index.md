---
title: Kalidas
ruleset: Ironsworn + Delve + Ironsmith
genre: Fantástico Medieval
player: Fede
pcs: Kalidas [PC:Kalidas]
start_date: 2026-04-29
last_update: 2026-04-29
---

# Kalidas

## Verdades

### El Mundo

La epidemia barrió el Viejo Mundo; no dejaba vida a su paso. Barcos zarpaban con miles de personas a bordo. Sin embargo, no se pudo contener la enfermedad. En muchos casos, las medidas que se tomaban eran crueles, como arrojar por la borda a cualquiera que mostrase el más mínimo síntoma. Hubo naves que se perdieron para siempre. Al final, los hombres y mujeres que sobrevivieron encontraron en las Tierras del Hierro un nuevo hogar. Hay quienes dicen que seremos malditos para siempre por las almas que dejamos atrás.

### Hierro

Repartidos por toda la tierra hay unos enigmáticos pilares de metal. Son grises como el hierro y suaves al tacto como un canto rodado. Nadie sabe para qué sirven. Hay quien dice que son tan antiguos como el propio mundo. Hay quienes los veneran, como los Sacerdotes del Hierro, que llevan a cabo sus rituales de juramento en ellos. La gran mayoría, sin embargo, hacen el signo de protección contra el mal de ojo y se apresuran cuando se cruzan con uno. Estos pilares no se deterioran y ni siquiera la hoja más afilada puede hacerles mella.

### Legados

Somos los primeros seres humanos que caminan por estas tierras.

### Comunidades

Somos pocas las personas que habitamos estas malditas tierras. Raras veces tenemos contacto con alguien fuera de nuestras aldeas o granjas y miramos a los extraños con sospecha.

### Líderes

Cada una de nuestras comunidades tiene su propio líder, al que llamamos supervisor. Cada siete primaveras, el pueblo revalida al supervisor en el cargo o elige a otra persona. Algunos supervisores llevan la corona de hierro a regañadientes, pero hay quien se vale de la intriga y la intimidación para conseguirla.

### Defensas

Los custodios son nuestros soldados, centinelas y milicia. Sirven a sus comunidades como ejército regular, encargándose de las guardias, patrullando las tierras circundantes y organizando las defensas en tiempos de crisis. La mayoría tienen vínculos fuertes con la comunidad. Luego están los custodios libres, que son personas que ejercen como mercenarios errantes y que se ofrecen para servir a una comunidad o proteger las caravanas.

### Artes Místicas

Hay quienes todavía encuentran consuelo en las viejas tradiciones. Recurren a las artes místicas para conocer cuál será el destino de su recién nacido o para encargar rituales que atraigan las buenas cosechas. Pero hay personas que, por miedo, actúan contra quienes sospechan que tienen el poder antiguo. Sin embargo, la mayoría de la gente cree que la auténtica magia ha desaparecido —si es que alguna vez en realidad existió—.

### Religión

Unos pocos habitantes del Hierro aún hacen signos de protección con las manos o murmuran oraciones, bien por costumbre, bien por tradición, pero la mayoría creen que los dioses nos abandonaron hace mucho tiempo.

### Los Primeros Nacidos

Los primeros nacidos gobiernan las Tierras del Hierro. Los elfos de los profundos bosques y los gigantes de las colinas toleran e incluso comercian —por ahora— con la gente del Hierro. El pueblo del Hierro teme el día en que los primeros nacidos decidan que los seres humanos ya no son bienvenidos.

### Bestias

Las bestias de antaño no son sino leyendas. Quienes se han internado en los profundos bosques y en las grandes montañas a veces han regresado con historias increíbles sobre criaturas monstruosas, pero está claro que no son más que alucinaciones. No existen tales cosas.

### Abominaciones

Los muertos no descansan en las Tierras del Hierro. Por las noches encendemos antorchas, esparcimos sal y apostamos centinelas en las puertas. No es suficiente. Ya están llegando.

## Personaje

**Demeanor**: Compasivo. Siento preocupación por otros y me preocupo de su bienestar.

**Motivación**: Perseguir coraje. Actúo de forma valiente y me aseguro de tenerlo presente.

**Trasfondos**

- *Avistado (Camino)*: Una vez me interné en el bosque y encontré uno de esos pilares antiguos, inmaculado. Al tocarlo perdí el conocimiento y desperté días después en un sitio desconocido con una capacidad de ver lo oculto.
- *Maestría con el Hacha (Talento de Combate)*: En agradecimiento por mi ayuda, un gigante me regaló una pequeña hacha para él, pero que tengo que empuñar con dos manos.
- *Invokar (Ritual)*: Una bruja descubrió un poder oculto en mí y me enseñó a controlarlo. Después descubrí que tenía otros planes para mí de los que no quería formar parte.

```
tbl: Región
  1: Las Islas del Escudo
  2: La Costa Quebrada
  3: Los Bosques Primigenios
  4: Las Tierras Anegadas
  5: El Refugio
  6: El Interior
  7: Las Colinas de la Tempestad
  8: Las Montañas de los Velos
  9: Los Yermos de la Devastación
tbl: Región d10=4 -> Vivo en las tierras anegadas
[Track:Conectar los Pilares|Juramento|Extremo 0/10]
```

## Sesión 1
*Fecha: 2026-04-25*

### Escena 1 *Alguien ha desaparecido en el asentamiento*

```
gen: Problema de asentamiento -> Alguien ha desaparecido
gen: Acción y Tema -> Amenazar Debilidad
? Se trata de una huida ? (50/50) Si
gen: Foco -> Bestia
gen: Nombre -> Flint
=> Flint ha desaparecido junto a una serie de bestias de carga, 
se sospecha que sea un traidor. [N:Flint|Traidor|Sospechoso]
```

Nos levantamos por la mañana con la noticia de la desaparición de Flint. Llevaba ya un tiempo dándole vueltas a mi experiencia con los pilares y tenía intención de salir del pueblo, así que debido a las circunstancias no lo dudé ni un momento.

- Yo lo buscaré y traeré de vuelta a las bestias
- Por favor, Kalidas, el asentamiento depende de tu éxito

```
@ Jurar por el hierro
d: Acción=3+Corazón+1=6 [Vínculo] vs Desafío=2,6 -> Éxito parcial
[PC:Kalidas|Impulso+1]
gen: Acción -> Perdurar
gen: Foco -> Camino
? Había alguien más con él ? (Probable) Sí
tbl: Cuantos? (d6) = 1
tbl: Nivel Desafío (d6)
  1-3: Problemático
  4-5: Peligroso
  6: Formidable
tbl: Nivel Desafío d6=2 -> Problemático
[Track:Traer de vuelta las bestias|Juramento|Problemático 0/10]
[Clock:Bestias de vuelta antes de la cosecha|Amenaza|0/10]
=> El camino estaba marcado, principalmente por las bestias. 
Flint estaba acompañado por alguien. Debía darme prisa, 
no recuperarlas a tiempo podría poner en peligro la 
supervivencia del asentamiento.
```

### Escena 2 *Inicio el camino*

```
[Track:Dar alcance a Flint|Problemático 0/10]
(note:El track "Dar alcance a Flint" es parte del juramento "Traer de vuelta a las bestias)
@ Viajar
d: Acción=1+Mente+1=5 [Vínculo] vs Desafío=1,5 -> Éxito parcial
=> Alcanzamos un lugar de paso 
  [Track:Dar alcance a Flint|3/10] 
  [PC|Suministros-1 (+4)]
```

```
tbl: Localización d100=50 -> Costa
tbl: Localización Costera d100=50 -> Ensenada
tbl: Descriptor Localización d100=93 -> Densa
? Encuentro a algo/alguien ? (Poco probable) -> Si
? Es un animal ? (Probable) -> Si
=> Llego a una zona de juncos altos. Escucho un ruido de un animal.
```

Seguía incesante las huellas del traidor cuando escuché un ruido que probenía de unos juncos. En esa zona abundaban los cangrejos, quizás podría disfrutar de una buena cena esa noche.

```
@ Reabastecerse
d: Acción=3+Mente=8 vs Desafío=8,10 -> Fallo, Paga el Precio
@ Paga el precio
? El animal me ataca ? (50/50) -> Sí
tbl: Nivel Desafío d6=1 -> Problemático
[Track:Cangrejo|Problemático 0/10]
```

Cuando trataba de emboscar al animal, descubrí que era uno de esos cangrejos gigantes con grandes pinzas.

### Escena 2 *Combate contra el cangrejo*

```
@ Entrar en liza
d: Acción=6+Corazón=8 vs Desafío=1,8 -> Éxito parcial
=> Tomar la iniciativa
```

```
@ Golpear
d: Acción=3+Hierro=5 vs Desafío=9,10 
-> Fallo, paga el precio
=> [PC|Salud -1 (4)]
@ Contratacar
d: Acción=3+Hierro=5 vs Desafío=4,10 [Maestría Hachas] 
-> Éxito parcial, inflinje daño y paga el precio
=> [Track:Cangrejo|6/10] [PC|Salud -1 (3)]
@ Afrontar el peligro, enfocado a defensa
d: Acción=6+Hierro=8 vs Desafío=9,9
-> Fallo con coincidencia
=> [Track:Cangrejo|Pasa a peligroso] [PC|Recursos -1]
@ Contratacar
d: Acción=4+Hierro=6 vs Desafío=1,4 -> Éxito total
=> [Track:Cangrejo|8/10]
@ Terminar la lucha
d: Track=8 vs Desafío=2,4 -> El cangrejo es derrotado
```

Lo que parecía un simple encuentro se tornó en pesadilla al enfrentarme a un cangrejo gigante. Sus enormes pinzas me hicieron daño y destrozaron parte de mi equipo.

```
@ Acampar
d: Acción=6+Suministros=9 vs Desafío=3,7 -> Éxito total
=> Recuperar salud y prepararme para el día siguiente (+1 Viajar)
  [PC|Salud +1 (5)]
```

La noche pasó tranquila. Pude curarme mis heridas y planteé el camino para el día siguiente.

### Escena 3 *Continuando el camino*

@ Viajar
d: Acción=2+Mente+1=6 vs Desafío=7,9 -> Fallo, paga el precio
tbl: Pagar el precio d100=Es doloroso
=> El atajo resulta peligroso, causándome fatiga [PC|Salud-1 (+4)]