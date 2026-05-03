---
title: Kalidas
ruleset: Ironsworn + Delve + Ironsmith
genre: Fantástico Medieval
player: Fede
pcs: Kalidas [PC:Kalidas]
start_date: 2026-05-01
---
# Kalidas

## Sesión 3
*Fecha: 2026-05-01* | *Duración: 1:30h*

### Escena 6 *El Asentamiento*

```
? Avanza la amenaza ? -> Sí
tbl: Avanzar la amenaza 1d100=20 -> Avanza
=> [Clock:Bestias de vuelta antes de la cosecha|Amenaza|1/10]
```

```
tbl: Asentamiento: Disposición 1d100=40 -> Cauteloso
tbl: Asentamiento: Primer Vistazo 1d100=06 -> Rodeado de piedras
=> 
  El pueblo aunque sencillo estaba bien cuidado, rodeado por
  una barrera de rocas que ayudaba a la defensa de animales salvajes.
```

Decidí acercarme, mostrando una predisposición al diálogo.

```
? Me reciben de forma amistosa ? (Poco probable) -> No
tbl: Personaje: Primer Vistazo 1d100=29 -> Modesto
tbl: Personaje: Actividad 1d100=74 -> Peleando
tbl: Personaje: Disposición 1d100=59 -> Desesperado
? Es un hombre ? (50/50) -> Sí
? Cuántos son ? 1d6=1
=> Una persona golpea a otra
```

Al acercarme, veo como están empujándo y pegándole a un hombre, que se arrastra por el suelo.

```
PC: "Eh, ¿qué os ha hecho ese pobre hombre para tratarlo así?"
gen: Acción/Tema -> Vengar/Supervivencia
N: "Este pobre infeliz ha tomado la justicia por su mano. Será castigado"

@ Persuadir, intento proponer un trato, hacer algo
d: Acción=Corazón+1+4=7 [Demeanor] vs Desafío=1,4 -> Éxito total
=>
  +1 Impulso (7)
  Aceptan y me proponen un trato
```

La persona me mira con desgana, pero parece encontrar una oportunidad en esta situación.

```
tbl: Asentamiento: Problema 1d100=Familias en conflicto
? Está relacionado con las bestias ? (50/50) -> No
gen: Acción/Descripción/Tema -> Resistir/Misterioso/Estrategia
? La persona con la que hablo, quiere atacar ? (Probable) -> No
=> 
  Cerca hay un lugar misterioso, del que surgen peligros. Unos quieren
  simplemente defenderse, otros quieren contratacar.

N: "Ha estado confabulando a mis espaldas, diciendo que no tengo valor. Sólo conseguirán que nos maten."
PC: "Yo os ayudaré, iré con vosotros y acabaremos con el peligro, pero os pediré algo a cambio."
N: "¿Qué es lo que quieres?"
PC: "La mitad de las bestias que habéis robado, pertenecen a mi poblado"
```

```
@ Persuadir
d: Acción=Corazón+3=5 vs Desafío=3,3 -> Éxito total con coincidencia
gen: Acción/Tema -> Guardia/Debilidad
=> 
  Acepta el trato. Parece sentir la culpa por el robo de las bestias.
  +1 Impulso (8)
  [Track:Traer de vuelta las bestias|Juramento|Problemático 6/10]
```

La persona acepta. Yo siento alivio porque veo más cerca la supervivencia de mi poblado, aunque no sé si el trato les parecerá justo a los míos.

Pasaré la noche allí y saldremos al día siguiente.

```
gen: Asentamiento: Nombre -> Canción de verano
tbl: Personaje: Detalles -> Aventurero
tbl: Personaje: Nombre -> Sola
tbl: Personaje: Detalles -> Conectado
tbl: Personaje: Nombre -> Themon
tbl: Cuantos vienen? 1d6=5
=> 
  [N:Sola|Preocupada por su pueblo|Aventurera]
  [N:Themon|Confabulador|Conectado a su pueblo]
```

Amaneció un día despejado, las gaviotas sonaban mientras planeaban su vuelo por la costa.

### Escena 7 *Camino al lugar*

```
@ Seguir un camino
d: Acción=Suministros+6=9 vs Desafío=5,9 -> Éxito parcial
=> 
  Llegamos al destino, pero se hizo más costoso de la cuenta.
  Soportar el dolor. Salud -1 (4)

@ Soportar el dolor
d: Acción=Salud+2=6 vs Desafío=4,10
=> Apretamos los dientes y continuamos
```

La bruma de la noche se levantó, pero el sol no calendaba lo suficiente como para endurecer el suelo. El camino resultó más duro de la cuenta y llegamos algo fatigados.

```
@ Descubrir un sitio
tbl: Nivel Desafío (1d6) -> Problemático
gen: Delve:Nombre -> Túmulo Infernal del Crepúsculo
gen: Delve:Tema/Dominio -> Túmulo Místico
[Track:Túmulo|Problemático|0/10]
```