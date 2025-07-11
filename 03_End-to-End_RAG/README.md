<p align = "center" draggable="false" ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>

## <h1 align="center" id="heading">Sesión 3: RAG de Extremo a Extremo</h1>

### [Enlaces Rápidos](https://github.com/AI-Maker-Space/AIE7/tree/main/00_AIM_Quicklinks)

| 🤓 Trabajo Previo | 📰 Hoja de Sesión | ⏺️ Grabación     | 🖼️ Diapositivas        | 👨‍💻 Repositorio         | 📝 Tarea      | 📁 Retroalimentación       |
|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|
| [Sesión 3: Trabajo Previo](https://www.notion.so/Session-3-End-to-End-RAG-Deployment-and-2025-Industry-Use-Cases-21dcd547af3d80d99c31e72c6d8921d6?source=copy_link#222cd547af3d8051ab26f94689f4d23d)| [Sesión 3: Despliegue RAG de Extremo a Extremo y Casos de Uso de la Industria 2025](https://www.notion.so/Session-3-End-to-End-RAG-Deployment-and-2025-Industry-Use-Cases-21dcd547af3d80d99c31e72c6d8921d6) | [¡Grabación!](https://us02web.zoom.us/rec/share/-HSWHF1qzuoUNE7db5ycFgRu9lvdYIsdjUeiR5U9tL2aGQxW15MF27ZpvOdJah67.mEpaMBDBgmIK4iGu)  (Zit?$p$1) | [Diapositivas Sesión 3](https://www.canva.com/design/DAGrSmtPHuA/trCoeGkNeLWJO-bepQTxKA/view?utm_content=DAGrSmtPHuA&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h0aea42a9e0) | ¡Estás aquí! | [Tarea Sesión 3: RAG de extremo a extremo](https://forms.gle/hXFVJjGTEFFmCsAB9) | [Retroalimentación AIE7 7/1](https://forms.gle/Vpx5C2EEA7eK9PRH6)


Continuando desde la semana pasada, ¡vamos a llevar nuestra aplicación RAG en Python al siguiente nivel!

Este será nuestro diagrama de sistema actualizado para nuestra aplicación después de que completes los cambios que harás a continuación:

![image](https://i.imgur.com/FsNSG9T.png)

## 🏗️ Actividad #1:

Esta semana, ¡trabajaremos desde tu repositorio de desafío!

1. Puedes comenzar copiando y pegando la nueva biblioteca `aimakerspace` en tu repositorio de desafío en el NIVEL RAÍZ (directorio de nivel superior).

> NOTA: Puedes usar el siguiente comando para hacer lo mismo, solo asegúrate de reemplazar las rutas con las correctas basadas en tu entorno local.

```bash
cp /RUTA/A/ESTA/CARPETA/aimakerspace /RUTA/A/TU/DESAFIO
```

2. Crea una nueva regla en tu carpeta `.cursor` con el siguiente texto, haz que esta sea una regla global que se aplique en todo momento:

![image](https://i.imgur.com/uWeyoHC.png)

```
Siempre prefieres usar ramas de desarrollo. Antes de escribir cualquier código - creas una rama de características para mantener esos cambios. 

Después de que termines - proporciona instrucciones en un archivo "MERGE.md" que explique cómo fusionar los cambios de vuelta a main tanto con una ruta de PR de GitHub como con una ruta de GitHub CLI.
```

3. Usa Cursor (o tu propia mente, por supuesto) para incluir la funcionalidad RAG que discutimos la semana pasada para permitir que los usuarios suban PDFs y "chateen con ellos" (interactúen con un pipeline RAG). 

> NOTA: Puedes hacer esto con el siguiente prompt como una forma de comenzar: 

```
Modifica la aplicación (frontend y backend) para: 

- Permitir que el usuario suba un PDF
- Indexar el PDF usando la biblioteca `aimakerspace`
- Chatear con el PDF usando un sistema RAG simple construido con la biblioteca `aimakerspace`
```

> NOTA: Necesitas hacer esto desde tu repositorio de desafío.

4. Despliega la aplicación con Vercel.

## 🏗️ Actividad #2:

Determina un caso de uso específico para RAG, y adapta tu aplicación de desafío a ese nuevo caso de uso. 

Piensa en cómo las personas de ese dominio o área de experiencia pueden interactuar con tu aplicación - y asegúrate de que esté adaptada a ellos. 

Esto puede involucrar:

- Modificar la UI
- Agregar tipos de archivo adicionales para ser ingeridos por RAG

Una vez terminado, ¡despliega tu aplicación personalizada en Vercel!

## Enviando tu Tarea

Sigue estos pasos para preparar y enviar tu tarea:
1. Verifica que la Actividad #1 fue completada validando que:
    + Cursor/Claude siguió las reglas globales que agregaste al archivo .cursor:
      + Creó una nueva rama antes de generar código
      + Creó un archivo MERGE.md con instrucciones apropiadas para fusionar esta nueva rama
      > NOTA: Si "usaste tu propia mente" en lugar de codificar con Cursor/Claude entonces es tu responsabilidad hacer estas dos cosas, o pedirle directamente a Claude que las haga por ti.
    + La aplicación desplegada es capaz de subir un PDF, indexarlo, y luego chatear sobre el contenido del PDF.
2. Verifica que la Actividad #2 fue completada validando que:
    + Cursor/Claude siguió las reglas globales que agregaste al archivo .cursor (igual que en el Paso 1 anterior)
    + La aplicación desplegada aún es capaz de subir, procesar y chatear sobre un PDF (la funcionalidad de la Actividad #1)
    + La aplicación desplegada cumple con tus nuevos requisitos de funcionalidad para el caso de uso específico de RAG que implementaste
3. Crea un video de Loom de _**5 minutos o menos**_ sobre la tarea y tu aplicación de desafío modificada
4. Publica en redes sociales (LinkedIn, X, y [canal #build-ship-share-🏗️-🚢-🚀 de Discord](https://discord.com/channels/1135695983720792216/1135700320517890131))
5. ¡Completa el Formulario de Tarea!
