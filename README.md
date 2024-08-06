API REST Loteria España
---------------------

### Request
```html
[https://lottorest.onrender.com](https://lottorest.onrender.com)
[https://lottorest.onrender.com/euromillon](https://lottorest.onrender.com/euromillon)
[https://lottorest.onrender.com/primitiva](https://lottorest.onrender.com/primitiva)
[https://lottorest.onrender.com/bonoloto](https://lottorest.onrender.com/bonoloto)
[https://lottorest.onrender.com/gordo](https://lottorest.onrender.com/gordo)
[https://lottorest.onrender.com/nacional](https://lottorest.onrender.com/nacional)
[https://lottorest.onrender.com/quiniela](https://lottorest.onrender.com/quiniela)
``` 

### Response
```html
{
  "euromillon": {
    "fechaEuromillon": "2024-08-06",
    "combinacionEuromillon": "01 18 27 41 50",
    "estrellas": "02 12",
    "codigoMillon": "FMZ81323"
  },
  "primitiva": {
    "fechaPrimitiva": "2024-08-05",
    "combinacionPrimitiva": "11 18 36 41 44 49",
    "complementarioPrimitiva": "35",
    "reintegroPrimitiva": "4",
    "joker": "0 091 862"
  },
  "bonoloto": {
    "fechaBonoloto": "2024-08-05",
    "combinacionBonoloto": "01 04 10 25 38 41",
    "complementarioBonoloto": "47",
    "reintegroBonoloto": "1"
  },
  "gordo": {
    "fechaGordo": "2024-08-04",
    "combinacionGordo": "21 34 36 41 48",
    "reintegroGordo": "8"
  },
  "nacional": {
    "fechaNacional": "2024-08-01",
    "primerPremio": "91351",
    "segundoPremio": "70909",
    "reintegroNacional": "1 7 9"
  },
  "quiniela": {
    "fechaQuiniela": "2024-08-04",
    "partidos": [
      {
        "equipo1": "Estados Unidos F",
        "equipo2": "Japón F",
        "goles": "1-0",
        "resultado": "1"
      },
      {
        "equipo1": "España F",
        "equipo2": "Colombia F",
        "goles": "2-2",
        "resultado": "X"
      },
      {
        "equipo1": "Canadá F",
        "equipo2": "Alemania F",
        "goles": "0-0",
        "resultado": "X"
      }
      ...
    ]
  }
}
``` 
