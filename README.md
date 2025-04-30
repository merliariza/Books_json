# Consola para ejecutar consultas LINQ sobre libros

Programa para ejecutar y mostrar los resultados de las consultas definidas en `LinqQueries.cs` sobre una colección de libros leída desde un archivo JSON.

## Funcionalidad

`Program.cs` permite:

- Ejecutar diferentes métodos de consulta de la clase `LinqQueries`.
- Imprimir los resultados en la consola de manera paginada (10 registros por pantalla).
- Visualizar estadísticas, como:
  - Total de libros por rango de páginas
  - Fecha mínima o máxima de publicación
  - Libros con ciertas características (categoría, año, etc.)

## Ejemplo de uso

1. En la clase `Main`, puedes activar/descomentar la consulta que desees ejecutar. Por ejemplo:

```csharp
ImprimirValores(queries.AllCollection());
