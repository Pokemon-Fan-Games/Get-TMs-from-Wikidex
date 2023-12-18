# Get-TMs-from-Wikidex

Esta es una pequeña aplicacion que usa beautifulsoup para scrapear bulbapedia, obtiene todos los MTs que puede aprender el pokemon ingresado y los agrega al archivo tm.txt PBS.

## Como usar la aplicacion

1. Descarga el archivo get_learnable_tms_from_wikidex.exe de la pestaña de releases.
2. Ejecuta el archivo get_learnable_tms_from_wikidex.exe.
3. Ingresa el nombre del pokemon del que quieres obtener los MTs.
   1. Puedes tambien seleccionar el archivo pokemon.txt de la carpeta PBS de tu proyecto y buscara las MTs para todos los pokemon que esten en el archivo.
      Tengan en cuenta que esta funcionalidad tarda bastante ya que hace una request a bulbapedia por cada pokemon. Si tienen todos los pokemon serian mas de 1000 requests
4. Seleciona el archivo tm.txt de la carpeta PBS de tu proyecto.
5. Haz click en el boton "Buscar MTs".
6. Si todo salio bien, el programa te mostrara un mensaje de que se han agregado los MTs al archivo tm.txt

### Recomiendo fuerte que hagas una copia de seguridad del archivo tm.txt antes de usar la aplicacion
