# ArchiHUB

ArchiHUB es una plataforma versátil de gestión documental que ofrece flexibilidad al permitir la configuración de diversos tipos de contenido, relaciones y estructuras de metadatos adaptadas a cada tipo de archivo. Además, ofrece soporte para una amplia variedad de formatos que incluyen documentos, videos, imágenes y audios. De manera predeterminada, ArchiHUB está configurado con soporte para el estándar internacional ISADG. Sin embargo, los campos de este estándar pueden ser personalizados y adaptados según las necesidades específicas de cada entidad o usuario en particular.

Además de lo mencionado, y con el objetivo de sacar el máximo provecho a los nuevos y emocionantes modelos de IA liberados por la comunidad, ArchiHUB cuenta con soporte para plugins. Esta funcionalidad permite expandir las capacidades de la aplicación, optimizando así el aprovechamiento de los documentos y extrayendo la máxima cantidad de información para facilitar su posterior recuperación.

Este desarrollo se beneficia de la experiencia en la administración de archivos de diversas entidades públicas en Colombia, tales como el Centro Nacional de Memoria Histórica, el Museo de Memoria, la Línea de Arte Ciencia y Tecnología de IDARTES, el Archivo General de la Nación, la Comisión de la Verdad y la Jurisdicción Especial para la Paz. A todas estas entidades y los equipos que las conformaron, un agradecimiento especial por hacerlo posible.

El proyecto está compuesto de varios repositorios descritos a continuación:

- [Iniciando con el aplicativo](https://github.com/Archihub-App/getting-started): recopilación de guías de uso, de instalación y empaquetados para su despliegue en diferentes arquitecturas.
- [Backend del aplicativo](https://github.com/Archihub-App/archihub-backend): Acá se encuentra la columna vertebral del proyecto. Este es el backend que hace posible la gestión de todo el sistema. El aplicativo por defecto viene con dos plugins, uno para el procesamiento de cualquier tipo de archivo y otro para generar inventarios del contenido a formato Excel.

Los plugins disponibles:

- [Transcripción automática](https://github.com/Archihub-App/transcribeWhisperX): Transcripción automática de audios y videos, con la posibilidad de visualizar la transcripción como subtitulos o en texto completo. La transcripción también puede ser traducida.
- [Segmentación de formularios con manuscritos](https://github.com/Archihub-App/documentSegment): Plugin que permite segmentar un documento identificando los bloques de texto, los manuscritos y las etiquetas correspondientes a esos manuscritos para finalmente generar un nuevo PDF con los manuscritos tachados siguiendo un protocolo especificado en el plugin.
- [OCR y segmentación para documentos](https://github.com/Archihub-App/ocrProcessing): Plugin que permite en primer lugar segmentar documentos (Imagenes, bloques de texto, pies de página, titulos, etc...) y hacer un OCR sobre esos bloques.
- [Extrancción de entidades nombradas](https://github.com/Archihub-App/nerExtraction): Plugin que usa la librería SpaCy para procesar las entidades nombradas de un OCR a documentos.
- [Segmentación de imágenes](#): PRONTO | Plugin para segmentar e identificar componentes de las imágenes.
- [Extracción de paletas de colores](#): PRONTO | Plugin para extraer paletas con los colores más importantes de una imagen o de un video segmentado por tiempo.
- [Radio en línea](#): PRONTO | Plugin para desplegar una radio en línea con material de audio que se encuentre catalogado en la herramienta.
- [Integración con WhatsApp](#): PRONTO | Plugin para usar WhatsApp o Telegram como medios de ingesta de información a la herramienta.
- [Identificación de rostros](#): PRONTO | Plugin para identificar rostros en material audiovisual, bien sea en imágenes o videos.
- [Extracción de articulos de Internet](#): PRONTO | Plugin para extraer y catalogar artículos de internet

---

ArchiHUB is a versatile document management platform that offers flexibility by allowing the configuration of various content types, relationships, and metadata structures tailored to each file type. Additionally, it provides support for a wide range of formats, including documents, videos, images, and audios. By default, ArchiHUB is configured with support for the international standard ISADG. However, the fields of this standard can be customized and adjusted according to the specific needs of each entity or user.

Furthermore, aiming to leverage the most out of the new and exciting AI models released by the community, ArchiHUB supports plugins. This functionality expands the application's capabilities, enhancing document utilization and extracting maximum information for easy retrieval.

This development draws from the experience in managing files from various public entities in Colombia, such as the National Center for Historical Memory, the Museum of Memory, the Art, Science, and Technology Line of IDARTES, the Truth Commission, the Nacional Archive, and the Special Jurisdiction for Peace. A special thanks to all these entities and the teams that comprised them for making this possible.