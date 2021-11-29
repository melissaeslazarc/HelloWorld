# HelloWorld

## Melissa Elvia Salazar Carrillo
## ITC

![alt text](image.jpg)
- First item
- Second item
- Third item
[title](https://www.example.com)
**bold text**

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

```
#include "Series.hpp"

Series::Series(){
  cantidadSeries = 0;
}

void Series::setCantidadSeries(int _cantidadSeries){
  cantidadSeries = _cantidadSeries;
}

int Series::getCantidadSeries(){
  return cantidadSeries;
}

void Series::addSerieAlArreglo(Serie _serie){
  if (cantidadSeries < 100){
    arrSeries[cantidadSeries] = _serie;
    cantidadSeries++;
  }
  else
    cout << "No se pudo añadir la serie" << _serie.str() << endl;

}
void Series::calcularCalificacionPromedioSerie(){
 //49.00 ciclo for donde va desde 0 menor que cantidad de series y mandamos llamar al método que calcula que ya tenemos en serie que calcula la calificacion, se va a usar el de serie, es nomas mandar al lamar al método 
}
void Series::leerArchivo( ){
//los archivos estos son provicionales, cambiar al de este grupo

}
void Series::reporteFrecuenciaYPromedioSeries(){

}

```

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
