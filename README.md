# Laboratorio 3.2: Extracción de Información con Beautiful Soup 🎬

![Logo de SetMagic Productions](https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_naranja@4x.png?raw=true)

## Contexto 📖

### Descripción
SetMagic Productions es una empresa especializada en la provisión de servicios integrales para la realización de rodajes cinematográficos y audiovisuales. Nos dedicamos a facilitar tanto el atrezzo necesario para las producciones como los lugares idóneos para llevar a cabo los rodajes, ya sea en entornos al aire libre o en interiores. 🌟

### Servicios Ofrecidos
- **Atrezzo Creativo:** Contamos con un extenso catálogo de atrezzo que abarca desde accesorios hasta muebles y objetos temáticos para ambientar cualquier tipo de escena. 🎭
- **Locaciones Únicas:** Nuestra empresa ofrece una amplia selección de locaciones, que incluyen escenarios naturales y espacios interiores como estudios y casas históricas. 🏞️
- **Servicios de Producción:** Ofrecemos servicios de producción audiovisual, incluyendo equipos de filmación, personal técnico y servicios de postproducción. 🎥

### Herramientas y Tecnologías ⚙️
Utilizamos herramientas de web scraping como **Beautiful Soup** y **Selenium** para extraer datos de sitios web y redes sociales especializadas en cine y producción audiovisual. También integramos APIs de plataformas de alquiler de locaciones y bases de datos de atrezzo. 🌐

### Objetivo 🎯
Nuestro objetivo es proporcionar a nuestros clientes una experiencia fluida y personalizada en la búsqueda de locaciones y atrezzo para sus proyectos audiovisuales.

---

## Lab: Extracción de Información con Beautiful Soup 🔍

En este laboratorio, enriquecerás la base de datos de atrezzo para ofrecer un servicio más completo. Utilizarás técnicas de web scraping para extraer información sobre objetos de atrezzo desde el siguiente enlace: [Atrezzo Vázquez](https://atrezzovazquez.es/shop.php?search_type=-1&search_terms=&limit=48&page=1).

### Pasos a Seguir

1. **Navegación y Extracción de Múltiples Páginas:**
   - Itera a través de las 100 primeras páginas y extrae la información deseada. 📄

2. **Verificación del Código de Estado de la Respuesta:**
   - Asegúrate de que la solicitud a la página web ha sido exitosa (código 200). Si no, imprime un mensaje de error y detén la ejecución. ❌

3. **Extracción de Información Específica:**
   - Extrae los siguientes detalles de cada objeto de atrezzo:
     - **Nombre del Objeto** 🏷️
     - **Categoría** 📂
     - **Sección** 🗂️
     - **Descripción** 📜
     - **Dimensiones** 📏
     - **Enlace a la Imagen** 🖼️

4. **Organización de los Datos en un Diccionario:**
   - Organiza los datos extraídos en un diccionario con las claves:
     - `"nombre"`
     - `"categoria"`
     - `"seccion"`
     - `"descripcion"`
     - `"dimensiones"`
     - `"imagen"`

5. **Almacenamiento de la Información en un DataFrame:**
   - Convierte los diccionarios en un DataFrame de Pandas, facilitando la manipulación y análisis de los datos. 📊

6. **Consideraciones Adicionales:**
   - Maneja errores durante el scraping. ⚠️
   - Realiza pausas entre solicitudes para evitar sobrecargar el servidor. ⏳
   - Almacena el DataFrame en un archivo CSV para su reutilización. 💾

---

## Resultados Esperados 🎉
El resultado final debe ser un DataFrame que contenga la información organizada sobre los objetos de atrezzo, permitiendo un análisis y manipulación eficaz.

![Ejemplo de DataFrame](https://github.com/Hack-io-Data/Imagenes/blob/main/02-Imagenes/BS/df_atrezzo.png?raw=true)

## Contribuciones 🤝
Las contribuciones son bienvenidas. Si deseas colaborar en este proyecto, no dudes en abrir un issue o enviar un pull request.

---
 
