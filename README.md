# Aprendizaje Automático

## ¿Qué hago después de haber clonado el proyecto?

Ejecute el comando `uv sync`. Este comando va a crear el _virtual environment_ y va a instalar todas las dependencias requeridas.

En caso de querer ejecutar este repositorio en Google Colab o alguna herramienta web donde `uv` no esté disponible se requiere instalar las dependencias manualmente.

Por ejemplo en Google Colab se debe agregar un bloque tal que:

```
!pip install <dependencia>
```

Para cada dependencia que se requiera adicional a las que el ambiente ya provee. Debido a esto la forma más sencilla es utilizando `uv`.
