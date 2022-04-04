# QuizzApp

App #3 del App Monthly Challenge 2022 de MoureDev

<table>
  <tr>
    <td>Highscores</td>
     <td>Select Quiz</td>
     <td>Playing</td>
  </tr>
  <tr>
    <td><img src="https://github.com/ArmandoS98/QuizzApp/blob/master/Screenshots/Screenshot_20220401-204731_QuizzApp.jpg" width=270 height=510></td>
    <td><img src="https://github.com/ArmandoS98/QuizzApp/blob/master/Screenshots/Screenshot_20220401-204738_QuizzApp.jpg" width=270 height=510></td>
    <td><img src="https://github.com/ArmandoS98/QuizzApp/blob/master/Screenshots/Screenshot_20220401-204920_QuizzApp.jpg" width=270 height=510></td>
  </tr>
 </table>

<table>
  <tr>
    <td>Good Answer</td>
     <td>Bad Answer</td>
     <td>Score</td>
  </tr>
  <tr>
    <td><img src="https://github.com/ArmandoS98/QuizzApp/blob/master/Screenshots/Screenshot_20220401-205047_QuizzApp.jpg" width=270 height=510></td>
    <td><img src="https://github.com/ArmandoS98/QuizzApp/blob/master/Screenshots/Screenshot_20220401-205118_QuizzApp.jpg" width=270 height=510></td>
    <td><img src="https://github.com/ArmandoS98/QuizzApp/blob/master/Screenshots/Screenshot_20220401-205144_QuizzApp.jpg" width=270 height=510></td>
  </tr>
 </table>

## Implementaciones

* Android con Kotlin
* Dagger Hilt
* Clean Architecture Android
* Android MVVM architecture
* Retrofit2
* Room

## Prueba el app!
Descargala de [aquí](https://github.com/ArmandoS98/QuizzApp/raw/master/app/release/QuizApp_Techun.apk)

### Requisitos:

* El diseño es de libre elección.
* La temática de las preguntas del cuestionario será de libre elección. Puede estar bien seguir un
  mismo tema (por ejemplo, preguntas sobre el universo "Harry Potter").
* En la pantalla inicial podrás comenzar a jugar o consultar el ranking de puntuaciones.
* El juego consistirá en 10 preguntas aleatorias con 3 respuestas y sólo una correcta. Recomendable
  crear más de 10 preguntas para que no siempre salgan las mismas. Cada vez que se responde a una
  pregunta, se pasará a la siguiente.
* Disponemos de 30 segundos para responder cada pregunta. El contador deberá aparecer en la
  pantalla, y si llega a 0 se tomará como respuesta incorrecta y se pasará a la siguiente pregunta.
* Al marcar una respuesta o finalizar el tiempo, se mostrará si se ha acertado o no la pregunta,
  dando feedback sobre cuál sería la respuesta correcta y navegando al cabo de un par de segundos a
  la siguiente pantalla.
* Sistema de puntuación:
    * Contador a 0 o respuesta incorrecta = 0 puntos.
    * Contador mayor 0 y respuesta correcta = [segundos restantes] puntos. Ej: Si quedaban 9
      segundos para finalizar la cuenta atrás y se acierta la pregunta, se asignan 9 puntos.
* Una vez finalizada la pregunta número 10 se mostrará en una nueva pantalla la puntuación final y
  se deberá introducir un nombre para guardarla de forma persistente (aunque cerremos la app). Hecho
  estos se mostrará la pantalla de ranking.
* La pantalla de ranking muestra ordenados de mayor a menor los 10 mejores resultados y el nombre
  guardado. Desde esta pantalla siempre se podrá navegar a la pantalla inicial.

## ¿Te interesa unirte?

* Ve más información  [aquí](https://github.com/mouredev/Monthly-App-Challenge-2022)
