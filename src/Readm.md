# PT15. Actividad Persistencia BBDD

## Básico

### Ten en cuenta ahora qué pasa cuando insertamos o modificamos un Álbum con un artista que no existe.¿Cómo modificarías el código para controlarlo?
**Respuesta**
No se aprecia que ocurra algo, pero es debido a que no existe en la base de datos restricción en casos de no existir el artist, no permite elegir hasta que se seleccione correctamente un artistId válido. A nivel del desarrollo faltaria la relación con la clase Artist en el cual debería formar parte de la clase Album.

**Solucion**
Implementar la Clase Artist e implementarse con el control de un IdArtist válido.

### 1.2 Añade la clase Artista y haz que se cargue el objeto Artista correspondiente a un álbum (como atributo de Álbum) al recuperar/leer un Álbum, y no solo el idArtista.
*DONE*

### Realiza todo el sistema CRUD (igual que con Álbum) pero con Track. También es necesario que crees las clases MediaType y Genre, ya que están relacionadas.
*DONE*