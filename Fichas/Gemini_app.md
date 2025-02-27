# :RiApps2AddFill: Gemini: _aplicación_

> [!question]+ **¿Qué es?**  
> Es una aplicación de Google que permite a los usuarios interactuar directamente con un asistente de inteligencia artificial conversacional impulsado por los modelos más importantes de _Gemini_.
> 
> - star! Una **interfaz de chatbot** diseñada para facilitar la comunicación con Gemini.
> - lk! Accede al chat de Gemini [**AQUÍ**](https://gemini.google.com/app?hl=es).

---
## :LiStarList: Características principales

- int! **Diseño intuitivo y fácil de usar**
- task! **Funciones avanzadas**: Personalización del modelo (`Gems`), búsquedas profundas en internet (`deep research`), integración de voz, multimodalidad, entre otras.
- inte! **Integración con servicios de Google**: Compatibilidad con herramientas como Gmail, Google Docs y Google Maps.
- plat! **Multiplataforma**: Disponible en versión web y como aplicación móvil para Android e iOS.

---
## :LiMousePointerClick: Interfaz de Usuario

La aplicación web de Claude, se compone de 3 partes principales:

![[Gemini_web_app.png]]

> [!upper]- **Menú superior**  
> En esta sección se concentran las **funcionalidades más básicas** de  la aplicación, las cuales son: 
> 
> ![[panel_superior_gemini_app.png]] 
> 
> 1. **Selector de modelo:** Permite elegir la versión de Gemini con la que se desea interactuar.
> 2. **Herramientas de Google:** Brinda acceso a otras aplicaciones del ecosistema de Google y a las opciones de configuración de la cuenta.

> [!side]- **Menú lateral**  
> Facilita la **navegación y el acceso a diversas funciones**.
>  
> ![[gemini_app_menu_lateral.png]]
> 
> Desde aquí es posible (principalmente):
> 1. Iniciar un nuevo chat
> 2. Acceder al **historial de conversaciones**, 
> 3. Acceder a `Gems` .
> 4. Crear `Gems`.
> 5. Ajustar configuraciones.

> [!conversation]- **Panel de conversación**  
> Muestra el **intercambio entre el usuario y el modelo de Gemini** seleccionado. Aquí se visualizan tanto las preguntas o solicitudes del usuario como las respuestas generadas por el chatbot.

> [!search]- **Barra de búsqueda**  
> Permite la **interacción directa** del usuario con el modelo.
> 
> ![[gemini_app_barra_busqueda.png]]
> 
> En particular, el usuario puede:
> 1. Redactar solicitudes.
> 2. Adjuntar archivos.
> 3. Utilizar el dictado por voz. 

---
## :FasUniversalAccess: Accesibilidad

> [!pay] **Ofrece dos versiones principales: _una gratuita_ y otra de pago llamada _Gemini Advance_.**

Para febrero de 2025, la versión _Gemini Advance_ 
- Tiene un costo de 20 dólares mensuales
- Para usuarios nuevos, tiene un descuento del 100% el primer mes.
- Incluye funcionalidades como: Gems, Deep Research, más y mejor integralidad con Google Workspace.

- lk! Consulta los planes [AQUÍ](https://gemini.google/advanced/?hl=es) 

---
## :RiFunctionAddFill: Funcionalidades interesantes para la investigación

1. **Creación de modelos  personalizados (:LiGem: `Gems`)**: Diseñar asistentes virtuales adaptados a roles específicos, como entrenador personal o editor de textos, personalizando su comportamiento y conocimientos según sus necesidades.
2. **Búsquedas profundas en internet (:RiGlobalLine: `Deep Research`)**: Recabar y analizar información relevante en la web y generar informes detallados con hallazgos clave y enlaces a las fuentes originales.


---
## :LiPenBox: Tutorial: _Investigación inicial sobre cualquier tema_

En este tutorial, aprenderás a utilizar **Gemini 1.5 Pro with Deep Research** para llevar a cabo una investigación exhaustiva en la web. Tomaremos como ejemplo el tema _Impacto de la IA en la educación_. Primero, crearemos un `gem` especializado para estructurar un prompt efectivo, luego utilizaremos dicho prompt para realizar la investigación inicial y, finalmente, modificaremos los resultados aprovechando la integración de Gemini con Google Docs.

- ! **Para realizar este ejercicio, es necesario contar con el plan _Gemini Advance_.**


> [!gem]- **Creación de** gem **para generación de prompt**
> 
> 1. **Acceso al Gestor de Gems:**
>     - Dirígete al menú lateral de Gemini y en la parte inferior selecciona `Administrador de Gems`.
>     - En la interfaz que aparece, presiona el botón `+ Nuevo Gem`.
> 2. **Configuración del Gem:**
>     - Copia y pega el nombre y las instrucciones en los campos correspondientes de la configuración.
>         
> 
> > [!pink]+ **Nombre del gem**  
> > `PromptGen Research`
> 
> > [!example]- **Instrucciones**
> > 
> > ```markdown
> > **Rol:**  
> > Eres un asistente experto en formulación de prompts, especializado en transformar temas generales en instrucciones de investigación profunda para *Gemini 1.5 Pro Deep Research*.
> > 
> > **Objetivo:**  
> > Convertir un tema de interés general proporcionado por el usuario en un prompt optimizado y efectivo que guíe a Gemini 1.5 Pro Deep Research en una investigación de alta calidad.
> > 
> > **Input del usuario:**  
> > Un tema de interés general (puede ser una palabra, una frase o una pregunta amplia).
> > 
> > **Output:**  
> > Un prompt (cadena de texto) listo para copiar y pegar en Gemini 1.5 Pro Deep Research. No debes responder otra cosa que no sea el prompt optimizado para su uso en Gemini 1.5 Pro Deep Research.
> > 
> > **Requisitos:**
> > 1. **Profundidad y Amplitud:**  
> >    - **Subtemas Clave:** Desglosa el tema en subtemas y formula preguntas directas sobre cada uno.  
> >    - **Diversidad de Fuentes:** Instruye a consultar diversas fuentes confiables, tales como:  
> >      - Artículos académicos (journals, conferencias).  
> >      - Libros y capítulos de libros.  
> >      - Fuentes de noticias de alta calidad (The New York Times, Reuters, BBC).  
> >      - Informes de organizaciones gubernamentales y ONGs.  
> >      - Datos estadísticos confiables (Banco Mundial, Eurostat, INEGI).  
> >      - Análisis de expertos (entrevistas, podcasts, videos de conferencias).  
> >      - Estudios de caso, perspectivas históricas, tendencias actuales y proyecciones futuras.
> > 
> > 1. **Consideraciones Adicionales:**  
> >    - El asistente **no** debe realizar la investigación, solo generar el prompt optimizado.  
> >    - Utiliza técnicas avanzadas de procesamiento de lenguaje natural para analizar el tema y estructurar el prompt.  
> >    - Usa fuentes de información actualizada.  
> >    - Si el tema es ambiguo o demasiado amplio, solicita al usuario que lo refine antes de generar el prompt final.
> > 
> > **Ejemplo de Prompt de Salida:**  
> > "Investiga exhaustivamente [Tema proporcionado por el usuario] y elabora un informe detallado. Divide el análisis en los siguientes subtemas: [Lista de subtemas]. Consulta diversas fuentes, incluyendo artículos académicos, libros, informes de organizaciones relevantes, noticias de alta calidad (The New York Times, Reuters, BBC) y datos estadísticos de fuentes reconocidas. Analiza las distintas perspectivas y debates actuales, identifica posibles sesgos y prioriza información de fuentes confiables. Presenta el resultado en un formato estructurado que incluya introducción, desarrollo (por subtemas), conclusión y referencias, acompañado de un análisis crítico de la información."
> > ```
> 
> 3. **Guardado y Uso del Gem:**
>     - Presiona el botón `Guardar Gem` para finalizar la configuración.
>     - Inicia un nuevo chat utilizando este `gem`.
> 4. **Introducción del Tema a Investigar:**
>     - En la barra de entrada, proporciona el tema que deseas investigar. Ejemplo:
>         
> 
> > [!info]+ **Tema a investigar**
> > ```
> > Impacto de la Inteligencia Artificial en la educación
> > ```  
> 
> 5. **Resultado Esperado:**
>     - Obtendrás un prompt estructurado para el uso de `Gemini 1.5 Pro with Deep Research`.
>         
>     - Revisa y ajusta el prompt según tus necesidades e intereses sobre el tema.
>         
> 
> - ! Este `gem` genera un prompt inicial para `Deep Research`, por lo que es recomendable revisarlo y adaptarlo a tus necesidades específicas antes de utilizarlo.

> [!gen]- **Investigación con** Deep Research
> 
> 1. **Uso del Prompt en Deep Research:**
>     - Copia el prompt generado por el `gem`.
>     - Inicia un nuevo chat en Gemini y selecciona el modelo `Gemini 1.5 Pro with Deep Research`.
>     - Pega el prompt en el chat y ajústalo según tus necesidades, modificando subtemas, enfoques u otros detalles relevantes.
> 2. **Ejecución de la Investigación:**
>     - Envía el prompt para iniciar el proceso de investigación.
>     - Gemini generará un plan de búsqueda que incluye las instrucciones de investigación.
> 3. **Revisión del Plan de Búsqueda:**
>     - Examina el plan de búsqueda con detalle.
>     - Si es necesario, ajusta el plan para afinar los resultados o enfocar la investigación en aspectos específicos.
> 4. **Inicio de la Investigación:**
>     - Una vez conforme con el plan, inicia la investigación.
>     - El proceso puede tardar varios minutos. Al finalizar, se desplegará un informe detallado junto con las fuentes consultadas.
> 5. **Revisión y Ajustes:**
>     - Analiza la información obtenida.
>     - Si los resultados no son satisfactorios, ajusta el prompt inicial y repite el proceso hasta obtener la información deseada.

> [!resource]- **Integración con** Google Docs
> 
> 1. **Exportación a Google Docs:**
>     - Al finalizar la investigación, en la parte superior del panel, pulsa el botón `Abrir en documentos`.
>     - Esto abrirá automáticamente el informe en un documento de Google Docs.
> 2. **Uso del Chat Integrado en Google Docs:**
>     - Dentro de Google Docs, encontrarás un botón en la parte superior para abrir un menú lateral con un chat integrado con Gemini.
>     - ![[docs_preguntar_gemini.png]]
>     - Puedes utilizar este chat para realizar preguntas adicionales, solicitar análisis más profundos o ajustar el contenido del informe.
> 3. **Exploración de Funcionalidades:**
>     - Experimenta con las sugerencias predefinidas del chat integrado.
>     - Utiliza la integración para modificar, ampliar o refinar el contenido directamente en Google Docs.

---
## :LiFileCheck: Referencias y recursos

1. zapier.com, fecha de acceso: febrero 24, 2025, [https://zapier.com/blog/google-gemini/#:~:text=Google%20Gemini%20is%20a%20family,audio%2C%20videos%2C%20and%20code.](https://zapier.com/blog/google-gemini/#:~:text=Google%20Gemini%20is%20a%20family,audio%2C%20videos%2C%20and%20code.)

2. What is Google Gemini? What you need to know - Zapier, fecha de acceso: febrero 24, 2025, [https://zapier.com/blog/google-gemini/](https://zapier.com/blog/google-gemini/)

3. ‎What Gemini Apps can do and other frequently asked questions, fecha de acceso: febrero 24, 2025, [https://gemini.google.com/faq](https://gemini.google.com/faq)

4. Google Gemini - Apps on Google Play, fecha de acceso: febrero 24, 2025, [https://play.google.com/store/apps/details?id=com.google.android.apps.bard](https://play.google.com/store/apps/details?id=com.google.android.apps.bard)

5. Gemini AI is coming to Google Messages: Here's how to use it - GeeksforGeeks, fecha de acceso: febrero 24, 2025, [https://www.geeksforgeeks.org/gemini-now-integrated-into-googles-messages-app/](https://www.geeksforgeeks.org/gemini-now-integrated-into-googles-messages-app/)

6. What is Google Gemini? | IBM, fecha de acceso: febrero 24, 2025, [https://www.ibm.com/think/topics/google-gemini](https://www.ibm.com/think/topics/google-gemini)

7. Talk naturally with Gemini Live - Android - Google Help, fecha de acceso: febrero 24, 2025, [https://support.google.com/gemini/answer/15274899?hl=en&co=GENIE.Platform%3DAndroid](https://support.google.com/gemini/answer/15274899?hl=en&co=GENIE.Platform%3DAndroid)

8. Use Gemini in Google Messages - Gemini Apps Help, fecha de acceso: febrero 24, 2025, [https://support.google.com/gemini/answer/14599070?hl=en](https://support.google.com/gemini/answer/14599070?hl=en)

9. AI Tools for Business | Google Workspace, fecha de acceso: febrero 24, 2025, [https://workspace.google.com/solutions/ai/](https://workspace.google.com/solutions/ai/)


