actividad: 

Todo el contenido de la actividad, debe ser entregado en un júpiter notebook, con sus correspondientes celdas de markdown para la documentación y celdas de código.
1. Implementación Práctica de RAG:
Recrea el ejemplo dado en un Jupyter Notebook o entorno de desarrollo similar, utilizando las librerías langchain_community.document_loaders, langchain_text_splitters, langchain_ollama, langchain_chroma, y langchain_google_genai.
Verifica el funcionamiento del sistema RAG respondiendo a preguntas relacionadas con el contenido de un documento X (deben proporcionar uno ustedes).
2. Exploración de Modelos de Embedding y LLM:
Experimenta con diferentes modelos de embedding disponibles en langchain_ollama (además de "nomic-embed-text") y analiza cómo impactan en la calidad de la recuperación de documentos.
Prueba con otros modelos de lenguaje de gran tamaño (LLM) compatibles con langchain_google_genai o langchain_ollama y compara sus respuestas y rendimiento.
3. Optimización del Separador de Texto:
Modifica los parámetros chunk_size y chunk_overlap del CharacterTextSplitter y observa cómo afectan a la creación de los documentos y, consecuentemente, a la precisión de las respuestas del LLM.
Investiga otros tipos de separadores de texto disponibles en Langchain y evalúa su idoneidad para diferentes tipos de documentos.
4. Gestión de Bases de Datos Vectoriales:
Explora las funcionalidades de Chroma para gestionar colecciones, persistencia de datos y realizar búsquedas más avanzadas (por ejemplo, filtrado de resultados).
Investiga otras bases de datos vectoriales compatibles con Langchain y considera sus ventajas y desventajas para diferentes casos de uso.
5. Refinamiento de Prompts:
Experimenta con diferentes prompt_template para el LLM, ajustando las instrucciones del sistema y los mensajes de IA/humano para mejorar la calidad y relevancia de las respuestas.
Implementa técnicas de ingeniería de prompts para guiar al LLM a proporcionar respuestas más precisas y útiles, incluyendo la atribución de fuentes cuando sea posible.