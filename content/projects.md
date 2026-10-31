---
title: "Proyectos"
---

Me gusta construir herramientas para problemas cotidianos y dejar espacio para probar ideas por curiosidad. Aquí conviven software en desarrollo, un proyecto de diseño y experimentos técnicos. Cada uno avanza a su ritmo; quiero ir documentando las decisiones, los errores y lo que voy aprendiendo.

## Papelería PAU

**Estado: en desarrollo, con módulos implementados y validados técnicamente; pendiente de pruebas en el entorno real y puesta en operación.**

Estoy desarrollando un sistema para digitalizar la operación de una papelería familiar. El reto es construir software útil, sencillo de operar y adecuado a un pequeño negocio: entender cómo se trabaja en el mostrador y acompañar ese proceso con herramientas mantenibles.

El proyecto ya cuenta con catálogo de productos, movimientos y conteos de inventario, interfaz móvil y de escritorio, compras y recepción de mercancía, ventas simplificadas, registro de gastos y movimientos de efectivo, y apertura y cierre de caja. Estas funciones tienen validaciones documentadas en el proyecto; todavía necesitan contrastarse con el uso cotidiano y los dispositivos reales.

El inventario móvil está pensado para trabajar desde dispositivos en la red local. Quedan pendientes las pruebas de campo y los ajustes que surjan al usarlo. La integración con WhatsApp es una posibilidad futura, aún sin implementar.

Utilizo **Java y Spring Boot, PostgreSQL, Vue y TypeScript, y Podman**, con herramientas de IA como apoyo al desarrollo. Es una oportunidad para aplicar especificaciones, revisión de código, pruebas y automatización a un problema cercano. Me interesa documentar cómo evolucionan los procesos administrativos y las pantallas a medida que se comprueban en la práctica.

## Proyectos Públicos y Open Source

También publico herramientas y experimentos en [GitHub](https://github.com/Naraku86). Me interesa compartir código y documentación que otras personas puedan estudiar, adaptar o mejorar. Estos son algunos ejemplos; cada repositorio conserva sus instrucciones, licencia y pendientes.

### EDCotizacion

**Estado: herramienta publicada, con versiones descargables. Licencia MIT.**

Una aplicación para preparar cotizaciones en PDF para pequeños negocios. Funciona de manera local y sin conexión, guarda los datos en SQLite y también puede ejecutarse en un servidor con contenedores. Combina Java, Spring Boot y una interfaz web, con plantillas y un historial de cotizaciones.

[Código, documentación y descargas de EDCotizacion](https://github.com/Naraku86/EDCotizacion).

### Michiratagame

**Estado: juego disponible en código, en evolución. Licencia MIT.**

Un clicker absurdo de michiratas, nacido de una comunidad de amigos y desarrollado con ayuda de IA. Combina TypeScript, mejoras, personajes, sonido y un tablero comunitario. Es un espacio para experimentar con mecánicas de juego y herramientas de desarrollo, con imágenes aportadas por la comunidad y arte conceptual generado con IA.

[Código y notas de desarrollo de Michiratagame](https://github.com/Naraku86/michiratagame).

### Themed Clock

**Estado: reloj de terminal publicado. Licencia MIT.**

Un reloj para Linux con diez temas animados, escrito en Python con su biblioteca estándar. Se adapta al tamaño de la terminal y permite configurar colores y efectos. Une mi gusto por las herramientas CLI con la personalización visual del escritorio. Las alarmas y el modo pomodoro permanecen como ideas futuras.

[Código y vistas previas de Themed Clock](https://github.com/Naraku86/themed-clock).

### Pasquín Lúdico

**Estado: catálogo con código y documentación públicos.**

Un sitio construido con Hugo para reunir juegos, imprimibles y pasatiempos libres o de bajo costo en español. Los textos originales del catálogo se comparten bajo CC BY-SA 4.0; las obras enlazadas y el software conservan sus propias licencias. Me interesa facilitar que otras personas encuentren materiales para jugar y compartir, respetando sus fuentes.

[Repositorio de Pasquín Lúdico](https://github.com/Naraku86/pasquin-ludico).

### Fall of Narco

**Estado: prototipo inicial en Godot.**

Un videojuego narrativo de aventura y exploración sobre la transformación de un pueblo mexicano ante la normalización de la violencia. El repositorio documenta un recorrido jugable inicial, desde el prólogo hasta la primera confrontación. Sigue en una fase temprana, con trabajo de narrativa, diseño y pruebas por desarrollar.

[Código y documentación de Fall of Narco](https://github.com/Naraku86/fall-of-narco).

## Los Monolitos

**Estado: anteproyecto y exploración de diseño.**

Estoy diseñando una jardinera interior con un sistema acuático y elementos arquitectónicos. El proyecto combina plantas, agua, concreto, piedra, iluminación y acabados minerales, con atención al mantenimiento, la funcionalidad y la seguridad.

Exploro alternativas para la circulación, filtración y tratamiento biológico del agua, y cómo integrar esos elementos en el espacio. Trabajo con bocetos, modelos y estudios visuales para comparar opciones y revisar decisiones. El diseño sigue abierto y necesita validaciones antes de llevarse a construcción.

Quiero documentar el proceso creativo y técnico: conceptos que cambian, alternativas descartadas, errores y evolución del diseño. Me gusta que un proyecto así obligue a pensar tanto en la composición como en lo que hará falta para cuidarlo después.

## Laboratorio: IA, Linux y Automatización

**Estado: experimentación continua.**

### Desarrollo asistido por agentes

Experimento con Codex CLI, Claude Code y agentes de programación para asistir en desarrollo, refactorización, pruebas, documentación y revisión de código. Parto de especificaciones, documentación técnica y estándares para dar contexto al trabajo y poder revisar el resultado.

También exploro agentes especializados y flujos con múltiples agentes: cómo repartir tareas, evaluar las propuestas e integrar cambios con supervisión humana. Me interesa registrar qué funciona, qué necesita más contexto y cuándo la intervención manual resulta más útil.

### Modelos locales y herramientas propias

Pruebo modelos locales mediante Ollama, herramientas CLI e integraciones de IA con herramientas propias. Busco automatizar tareas repetitivas y comprobar qué aportan al trabajo cotidiano. Estas pruebas son un espacio para conocer posibilidades, límites y aprendizajes; las decisiones arquitectónicas y la revisión del código siguen bajo responsabilidad humana.

### Calidad y seguridad

A partir de mi experiencia con SonarQube, análisis estático y lineamientos OWASP, exploro cómo los agentes pueden apoyar la revisión de código, el análisis de hallazgos y la propuesta de correcciones. Cada propuesta necesita validación técnica y revisión humana antes de integrarse.

### Infraestructura propia

Experimento con servidores Linux y VPS, contenedores con Podman, despliegue de aplicaciones, redes privadas y conectividad remota. También me interesan los servicios autohospedados y la automatización de infraestructura.

Mantener infraestructura propia me permite aprender cómo encajan las piezas y publicar aplicaciones con mayor autonomía. Quiero ir dejando notas sobre despliegues, mantenimiento y decisiones técnicas, sin exponer configuraciones privadas.

## Trabajo Profesional

Mi experiencia profesional se centra en Java, arquitectura backend y sistemas financieros de misión crítica. He trabajado en trading electrónico, market data en tiempo real, conectividad con mercados, mensajería empresarial y middleware financiero.

También he participado en automatización financiera, plataformas para estrategias automatizadas, monitoreo y sistemas de alta disponibilidad. Combino el desarrollo con la coordinación técnica, la integración y la calidad del código. El detalle de tecnologías, protocolos y áreas de experiencia está en mi [CV](/cv/).
