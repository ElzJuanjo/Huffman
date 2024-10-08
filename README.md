# ALGORITMO DE HUFFMAN

**Para su ejecución requiere Java Development Kit (JDK) en su versión 21 o posterior:** [Sitio Oficial](https://www.oracle.com/co/java/technologies/downloads/)

## DESCRIPCIÓN
Este proyecto implementa el **algoritmo de compresión de Huffman**, una técnica utilizada para reducir el tamaño de archivos de texto. El algoritmo construye un árbol binario a partir de la frecuencia de los caracteres en el archivo, generando un conjunto de códigos binarios optimizados para representar cada carácter. La aplicación permite tanto **comprimir** como **descomprimir** archivos de texto, ofreciendo una interfaz gráfica amigable para visualizar la codificación y el árbol generado.

### Características principales:
- **Compresión de archivos**: Convierte un archivo de texto en una versión comprimida utilizando el algoritmo de Huffman.
- **Descompresión de archivos**: Recupera el contenido original de archivos comprimidos con la extensión `.huff`.
- **Visualización**: Muestra el árbol binario generado y la frecuencia de cada carácter.
- **Exportación**: Permite guardar tanto archivos comprimidos como el archivo descomprimido.

## VISTA PREVIA

![huffman1](https://github.com/user-attachments/assets/6b85ad00-417a-4966-b4b7-c933b9d5d168)

## FUNCIONALIDAD
» Haz clic en uno de los botones principales: **COMPRIMIR** | **DESCOMPRIMIR**

### COMPRIMIR
» Selecciona un archivo de texto cualquiera. Para el ejemplo, se usará el siguiente archivo de prueba:

![huffman2](https://github.com/user-attachments/assets/7ece27dc-ecb7-4812-a608-782cecbe8e18)

» La información se actualizará y se activarán los botones: **GUARDAR** | **VER INFO** | **VER ÁRBOL**.

![huffman3](https://github.com/user-attachments/assets/aeae8e62-ae78-4b60-8496-9662982f7486)

#### GUARDAR
» Exporta el archivo comprimido en formato `.huff`, o bien, en un archivo `.txt` si se trata de la información recuperada.

#### VER INFO
» Permite visualizar:
* Frecuencia de cada carácter junto con su camino en el árbol de Huffman.
* Mensaje original o recuperado del archivo.

![huffman4](https://github.com/user-attachments/assets/2645279b-265a-4642-a3b7-0c541219a9e0)

#### VER ÁRBOL
» Brinda una representación gráfica del árbol generado para la codificación.

![huffman5](https://github.com/user-attachments/assets/536becb0-7289-42a8-bcb4-61b9da137345)

### DESCOMPRIMIR
» Para descomprimir correctamente, el archivo debe tener la extensión `.huff` y haber sido generado con esta aplicación.  
» El contenido que se genera en los botones tras la descompresión es el mismo que se enseñó anteriormente.

##### NOTAS
* Las letras mayúsculas se convierten a minúsculas y los acentos se quitan.
* Los caracteres especiales no pertenecientes al conjunto ASCII se eliminan.
* El carácter `\` también se elimina, ya que se usa para formatos especiales en programación.
