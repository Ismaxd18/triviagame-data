# triviagame-data
Datos de preguntas para el juego TriviaGo organizados en archivos JSON por categorías y niveles de dificultad

# TriviaGo Data

Este repositorio contiene los archivos JSON con las preguntas para el juego TriviaGo, organizadas por categorías y niveles de dificultad.

## Estructura

Cada archivo JSON corresponde a una categoría diferente y contiene preguntas organizadas en tres niveles de dificultad (1, 2 y 3).

- `ciencia.json`: Preguntas sobre ciencia
- `historia.json`: Preguntas sobre historia
- `entretenimiento.json`: Preguntas sobre entretenimiento
- `deportes.json`: Preguntas sobre deportes
- `geografia.json`: Preguntas sobre geografía
- `tecnologia.json`: Preguntas sobre tecnología

## Formato de los Archivos

Cada archivo JSON tiene la siguiente estructura:

```json
{
  "id": "nombre_categoria",
  "name": "Nombre de la Categoría",
  "color": "#hexcolor",
  "levels": [
    {
      "level": 1,
      "questions": [
        {
          "id": "q1-1",
          "question": "¿Pregunta?",
          "options": ["Opción 1", "Opción 2", "Opción 3", "Opción 4"],
          "answer": 2,
          "difficulty": "fácil",
          "points": 2000
        },
        // más preguntas...
      ]
    },
    // más niveles...
  ]
}UsoEstos archivos están diseñados para ser consumidos por la aplicación TriviaGo mediante peticiones fetch.ActualizaciónPara añadir o modificar preguntas, simplemente edita el archivo JSON correspondiente y realiza un commit.## Paso 3: Crear los Archivos JSON

Después de crear el repositorio, deberás crear los siguientes archivos:

1. `ciencia.json`
2. `historia.json`
3. `entretenimiento.json` 
4. `deportes.json`
5. `geografia.json`
6. `tecnologia.json`

Para cada archivo, usa el formato de base de datos que ya tienes en tu código. Por ejemplo, para `ciencia.json`:

```json
{
  "id": "ciencia",
  "name": "Ciencia",
  "color": "#3498db",
  "levels": [
    {
      "level": 1,
      "questions": [
        {
          "id": "c1-1",
          "question": "¿Cuál es el elemento químico con símbolo H?",
          "options": ["Helio", "Hidrógeno", "Hafnio", "Holmio"],
          "answer": 1,
          "difficulty": "fácil",
          "points": 2000
        },
        // resto de preguntas nivel 1...
      ]
    },
    {
      "level": 2,
      "questions": [
        // preguntas nivel 2...
      ]
    },
    {
      "level": 3,
      "questions": [
        // preguntas nivel 3...
      ]
    }
  ]
}
