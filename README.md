![Mi computadora](banner.png)

Oscar-QA-Portfolio
Portafolio profesional con proyectos enfocados en diseño y ejecución de pruebas manuales, incluyendo validación de APIs y reporte de bugs.

BIO

Soy Quality Assurance Tester en formación, con experiencia previa en logística internacional y comercio exterior.  
Mi trayectoria me ha permitido desarrollar habilidades en la optimización de procesos, documentación clara y cumplimiento normativo, que ahora aplico en el aseguramiento de calidad de software.  

Manejo herramientas como **JIRA, Postman, Selenium, Python y SAP**, y he trabajado en proyectos de pruebas manuales, validación de APIs y reporte de bugs.  
Actualmente estoy en transición hacia un rol de QA Engineer, integrando mi experiencia en procesos con competencias técnicas para aportar soluciones confiables y eficientes.  

Me caracterizo por ser **pragmático, metódico y orientado a la mejora continua**, siempre buscando claridad en la comunicación y resultados medibles en cada proyecto.

Proyecto 1
Pruebas de API con Urban.Grocers

**Objetivo:** Diseñar y ejecutar casos de prueba para dos requisitos del backend:
1. **Kits:** Validar el endpoint `POST /api/v1/kits/:id/products` con límite de 30 productos únicos.
2. **Servicios de entrega:** Validar el endpoint `POST /order-and-go/v1/delivery` con parámetros obligatorios (`productsCount`, `productsWeight`, `deliveryTime`).

**Acciones realizadas:**
- Analicé los requisitos del backend (documento oficial de 7 páginas).
- Diseñé entre 14–20 casos de prueba para los kits y 15–25 para los servicios de entrega.
- Ejecuté pruebas en **Postman** con distintos cuerpos JSON.
- Reporté errores en **JIRA**, clasificándolos por severidad (crítico, grave, menor, trivial).

**Casos destacados:**
- Agregar 30 IDs distintos a un kit → 200 OK.  
- Intentar agregar el ID número 31 → 400 Bad Request con mensaje “No más de 30 artículos por conjunto”.  
- Agregar producto inexistente (ej. ID 9999) → 400 Bad Request.  
- Solicitud de entrega con parámetros válidos → 200 OK con `isItPossibleToDeliver: true`.  
- deliveryTime fuera de rango (ej. 23) → 400 Bad Request.  

**Aprendizajes:**
- Cómo derivar criterios de aceptación desde requisitos de backend.  
- Importancia de cubrir casos positivos, negativos, límites y clases de equivalencia.  
- Documentar errores con evidencia clara en JIRA y vincularlos al proyecto.  


Proyecto 2
Pruebas de Car Sharing (Urban Routes)

**Objetivo:** Validar el diseño y la funcionalidad del formulario de reserva de automóviles y sus ventanas asociadas, asegurando que cumplan con los requisitos definidos.

**Entornos de prueba:**
- Google Chrome (800x600)
- Firefox (1920x1080)

**Acciones realizadas:**
1. Creación de lista de comprobación para el diseño del formulario de reserva (opción “Lujo”).
2. Lista de comprobación para las ventanas “Método de pago” y “Agregar tarjeta” usando clases de equivalencia y valores límite.
3. Casos de prueba para el botón **Reservar**, incluyendo escenarios positivos y negativos.
4. Casos de prueba para la función de reserva de automóviles.
5. Ejecución de pruebas en ambos entornos y documentación de resultados (APROBADO / NO APROBADO).
6. Reporte de errores en **JIRA**, vinculando IDs en la hoja de cálculo.

**Errores detectados:**
- Ventanas emergentes con inconsistencias en diseño.
- Falta de temporizador en “Agregar licencia de conducir” (requisito no implementado).
- Diferencias menores entre diseño en Figma y requisitos funcionales.

**Aprendizajes:**
- Importancia de separar pruebas de diseño y funcionalidad según entorno.
- Uso de listas de comprobación exhaustivas para validar interfaz.
- Documentación clara de bugs en JIRA y vinculación con casos de prueba.

Experiencia previa en logística

Aunque mi portafolio se centra en QA, mi trayectoria en logística me permitió desarrollar habilidades transferibles:

- **Optimización documental en exportaciones**  
  Reduje errores en pedimentos y carta porte mediante controles en SAP y Excel y acercamiento con proveedores.  
  *Habilidad transferible:* validación de datos y documentación precisa.

- **Gestión de procesos en Owens América**  
  Coordiné exportaciones e importaciones, asegurando cumplimiento normativo y reducción de tiempos de entrega.  
  *Habilidad transferible:* análisis de procesos y comunicación efectiva con equipos.

- **Control de archivo en SAT Aduana Interior Monterrey** (servicio social) 
  Implementé un sistema de clasificación que mejoró la trazabilidad de documentos oficiales.  
  *Habilidad transferible:* organización, trazabilidad y enfoque en calidad.

  Habilidades técnicas

QA & Testing
- JIRA → gestión de casos de prueba y reporte de bugs  
- Postman → validación de APIs, pruebas positivas/negativas, valores límite  
- Selenium → automatización de pruebas funcionales (en formación)  
- Python → scripts básicos aplicados a QA  
- Diseño de casos de prueba → positivos, negativos, equivalencia, valores límite  
- Clasificación de severidad de errores → crítico, grave, menor, trivial  

Documentación & Herramientas
- GitHub → portafolio digital y control de versiones  
- Notion / Google Docs / Excel → documentación de pruebas y listas de comprobación  
- Microsoft Office → reportes y control documental  

Logística & Procesos
- SAP → gestión de procesos y validación documental  
- Gestión documental aduanal → organización y trazabilidad de información  
- Cumplimiento normativo (NOMs/SAT) → validación contra requisitos  

Idiomas
- Español: nativo  
- Inglés: avanzado (uso laboral, conversacional y escrito)  
- Francés: nivel B1 certificado (comprensión y comunicación intermedia)  

Soft Skills
- Atención al detalle → detección de inconsistencias en requisitos y diseño  
- Comunicación clara → reportes de bugs comprensibles para equipos de desarrollo  
- Análisis de procesos → aplicar lógica de negocio en pruebas  
- Adaptabilidad → trabajo en entornos cambiantes e internacionales  

Pueden ponerse en contacto via e-mail: oscarramirez649@gmail.com
Y mi perfil de Linked in www.linkedin.com/in/oscar-alejandro-ramírez-vergara-679992171
