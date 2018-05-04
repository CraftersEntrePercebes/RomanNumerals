# Kata Roman Numerals
Descripción de la kata: http://codingdojo.org/kata/RomanNumerals/

Slides: https://speakerdeck.com/islomar/kata-de-numeros-romanos-y-tpp


## Objetivos
* El objetivo de este coding dojo es practicar los baby steps e introducirse en la Transformation Priority Premise (TPP), experimentando las posibles diferencias entre su aplicacin o no.
* Por otra parte, este coding dojo se organiza para **APRENDER** en un entorno seguro, donde podamos probar cosas que en nuestro día a día no nos permita nuestro entorno (puede ser una determinada técnica, o una librería, atajos del IDE, un nuevo concepto, pair programming, etc.).
* El objetivo **NO** es acabar la kata, ni crear el mejor código del mundo.


## Requisitos
Es necesario venir con tu portátil, tu IDE favorito instalado y con un entorno básico ya configurado. Para esto último podéis usar los esqueletos existentes en el repositorio www.github.com/CraftersEntrePercebes/esqueletos-katas (a continuación explicamos cómo usarlos).


## Cómo montar el entorno
Evidentemente puedes hacerlo como quieras, pero de cara a poder compartir tu código con otras personas, te recomendamos que sigas los pasos explicados aquí: https://github.com/CraftersEntrePercebes/esqueletos-katas#c%C3%B3mo-usarlo


## Reglas
* Se deberá **trabajar en parejas**. Si hubier un número impar de personas, se pondrá en trieja. Lo ideal sería crear parejas combinando gente con más experiencia en general (ya sea en testing o en desarrollo de software) con gente con menos.
* Deberá trabajarse obligatoriamente con TDD (Test-Driven Development).
* Se realizarán varias iteraciones, pudiéndose cambiar de pareja si así se desea (de hecho sería lo ideal).
* Tras cada iteración, recordad dar las gracias a vuestra pareja por la sesión :-)


## Qué NO debes esperar de este coding dojo
* No es una clase magistral ni un curso, ya que lo aprendas depende principalmente de ti. Habrá dos facilitadores para refrescar en qué consiste TDD, exponer TPP, proponer un ejercicio práctico (la kata) y crear el contexto adecuado para que se dé el aprendizaje.
* No es un lugar donde aprender un nuevo lenguaje. Al menos una de las dos personas de la pareja debe encontrarse cómodo con el lenguaje de programación elegido.
* No es un lugar donde aprender a configurar un entorno de desarrollo.


## Cómo comenzar
1. **Encontrar una pareja/trieja**.
2. **Decidir** qué **lenguaje de programación** vais a usar y en qué portátil.
3. **Lee cuidadosamente el problema abajo descrito** (o aquí: ) y en caso de tener alguna duda, consultad con los facilitadores.


## Descripción de la kata

La kata consiste en escribir una funcióin que convierta de números decimales a números romanos. E.g.:
``` 
    1 --> I
    10 --> X
    7 --> VII
    1949 --> MCMXLIX
    2018 --> MMXVIII
```
etc.

[Aquí](http://www.novaroma.org/via_romana/numbers.html) puedes encontrar una descripcin entera para refrescar cómo funcionan los números romanos (así como una calculadora) [this useful reference website].

No es necesario convertir números mayores de 3000.


### Test cases

| Input | Resultado |
|-------|-----------|
| 1     | I         |
| 10    | X         |
| 7     | VII       |
| 1949  | MCMXLIX   |
| 2018  | MMXVIII   |



### Bonus track
* Implementar la conversin inversa: de número romano a número decimal  

