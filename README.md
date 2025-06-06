Bitwarden to Kaspersky CSV Converter
====================================

A simple, client-side web tool to convert a .csv export from Bitwarden into a format compatible for import into Kaspersky Password Manager.

English
-------

### What is this?

This is a single-page HTML tool that allows you to convert your Bitwarden password vault, exported as a CSV file, into the specific CSV format required by Kaspersky Password Manager. This is useful because Kaspersky does not natively support direct imports from Bitwarden.

### ✨ Key Features

*   **Easy to Use**: Simple interface to upload, convert, and download your file.
*   **Privacy First**: The entire conversion process runs locally in your web browser. Your data, passwords, and personal information are **never** uploaded to any server. It's completely private.
*   **Format Correction**: Automatically maps Bitwarden fields to Kaspersky's required format (url,username,password,name,extra).
*   **Data Validation**: Skips entries without a URL, as this is a mandatory field for Kaspersky, preventing import errors.

### How to Use (for Non-Technical Users)

You don't need to install any software to use this tool.

1.  Go to the GitHub repository.
2.  Download the index.html file to your computer.
3.  Find the downloaded index.html file on your computer and double-click it. It will open in your default web browser (like Chrome, Firefox, Edge, etc.).
4.  Follow the on-screen instructions:
    *   Export your vault from the Bitwarden app in .csv format.
    *   Upload that .csv file to the tool.
    *   Click the "Convert" button.
    *   A new file named kaspersky\_import.csv will be downloaded automatically. 
5.  Import this new file into Kaspersky Password Manager.
    

### Limitations
*   The tool is designed to convert **login** type entries only. Secure Notes, Cards, or Identities may not be transferred.
*   One-Time Password (TOTP) keys are not migrated directly but a note is added to the "extra" field to remind you to transfer them manually.

Español
-------

### ¿Qué es esto?
Esta es una herramienta web de una sola página que te permite convertir tu bóveda de contraseñas de Bitwarden, exportada como un archivo CSV, al formato CSV específico que requiere Kaspersky Password Manager. Esto es útil porque Kaspersky no tiene una opción nativa para importar directamente desde Bitwarden.

### ✨ Características Principales
*   **Fácil de Usar**: Una interfaz sencilla para subir, convertir y descargar tu archivo.
*   **La Privacidad es lo Primero**: Todo el proceso de conversión se ejecuta localmente en tu navegador. Tus datos, contraseñas e información personal **nunca** se suben a ningún servidor. Es completamente privado.
*   **Corrección de Formato**: Asigna automáticamente los campos de Bitwarden al formato requerido por Kaspersky (url,username,password,name,extra).
*   **Validación de Datos**: Omite las entradas que no tienen una URL, ya que este es un campo obligatorio para Kaspersky, previniendo errores de importación.

### Cómo Usarlo (para usuarios no técnicos)
No necesitas instalar ningún programa para usar esta herramienta.
1.  Ve al repositorio de GitHub.
2.  Descarga el archivo index.html a tu computadora.
3.  Busca el archivo index.html descargado en tu computadora y haz doble clic sobre él. Se abrirá en tu navegador web (como Chrome, Firefox, Edge, etc.).
4.  Sigue las instrucciones en pantalla:
    *   Exporta tu bóveda desde la aplicación de Bitwarden en formato .csv.
    *   Sube ese archivo .csv a la herramienta.
    *   Haz clic en el botón "Convertir".
    *   Un nuevo archivo llamado kaspersky\_import.csv se descargará automáticamente.
5.  Importa este nuevo archivo en Kaspersky Password Manager.
    

### Limitaciones

*   La herramienta está diseñada para convertir únicamente entradas de tipo **login**. Las Notas Seguras, Tarjetas o Identidades podrían no transferirse.
    
*   Las claves de Contraseña de un Solo Uso (TOTP) no se migran directamente, pero se añade una nota en el campo "extra" para recordarte que las transfieras manualmente.
