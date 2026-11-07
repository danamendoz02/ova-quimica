# +Edu3 — OVA de Química General

Prototipo web educativo para explorar contenidos básicos de Química General.

## Cómo abrirlo
1. Descarga y descomprime `edu3_ova_quimica.zip`.
2. Abre la carpeta.
3. Haz doble clic en `index.html` para abrirlo en tu navegador.

No necesita instalar dependencias ni ejecutar un servidor.

## Publicarlo con GitHub Pages
1. Crea un repositorio en GitHub, por ejemplo `edu3-ova-quimica`.
2. Sube `index.html`, `styles.css`, `script.js` y este `README.md` a la raíz del repositorio.
3. En GitHub entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages genere el enlace del sitio.

## Funciones incluidas
- Inicio con bienvenida y progreso general.
- Siete unidades de Química General.
- Lecciones con explicaciones y ejemplos.
- Mini cuestionario con retroalimentación inmediata.
- Monedas, insignias y registro del avance.
- Diseño adaptable a celular, tableta y computador.
- Guardado local del progreso mediante `localStorage`.

## Nota sobre conectividad
El prototipo es una página estática y sus funciones principales trabajan en el navegador. El progreso se guarda en el dispositivo mediante `localStorage`. Para una versión institucional con sincronización entre dispositivos o cuentas, se necesitaría implementar un backend. La tipografía externa puede requerir conexión; si no hay Internet, el navegador utilizará una fuente alternativa.

## Personalización
Edita `script.js` para cambiar los temas, ejemplos, preguntas y respuestas. Edita `styles.css` para cambiar colores y apariencia.
