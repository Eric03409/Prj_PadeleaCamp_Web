SBM_Global-Design-System
Este repositorio actúa como el Sistema de Diseño Base (Design System) y el Template de Código CSS para todos los proyectos digitales de SBM (Oficina de Proyectos con IA).

Su objetivo es asegurar la consistencia visual y acelerar el desarrollo de Proyectos y MVPs como Ad Zone, Portafy, Score Metrics, etc., siguiendo el WoW 1.0.

🚀 Way of Working (WoW) - Versión 1.0
Este flujo define cómo pasamos de la idea al código utilizando las herramientas estandarizadas por SBM.

Fases Clave

Fase	Herramientas Principales	Objetivo de la Fase
DISEÑO	Miro, Figma, Canva	Definir la estructura (Wireframes) y la apariencia final (Prototipo) utilizando conceptos de CSS como FLEXBOX (Auto Layout) y RESPONSIVE DESIGN (Constraints).
CONSTRUCCIÓN	VS Code (CSS)	Traducir el diseño en código CSS reutilizable, utilizando las propiedades de espaciado (PADDNG y MARGIN) y de distribución (display: flex; y @media query).
CONTROL	Azure DevOps	Almacenamiento centralizado, colaboración y control de versiones del código fuente.
📁 Estructura del Repositorio (Carpetas)
Este repositorio contiene la plantilla básica de CSS. Al clonarlo, ya tienes el 80% de la estructura de estilos necesaria para cualquier nuevo proyecto.

Carpeta	Propósito del Contenido	Ejemplos de Archivos
01_Base	Configuración Inicial. Contiene CSS para asegurar que el navegador funcione de forma uniforme (reseteo de estilos).	reset.css, tipografia.css
02_Tokens	Variables Globales. Almacena las DESIGN TOKENS de SBM (colores, fuentes y espaciados clave) para facilitar cambios masivos.	variables.css
03_Layout	Estructura de la Página. Contiene el CSS para las estructuras principales (encabezado, pie de página, contenedores de contenido) y reglas FLEXBOX / CSS GRID.	header.css, grid.css
04_Componentes	Piezas Reutilizables. Estilos para los elementos de ATOMIC DESIGN. Aquí está el código final de piezas clave.	button.css (Estilo base del BUTTON), card.css, form.css
🛠️ Flujo de Trabajo con Código
La rutina diaria de un constructor (usuario de VS Code) para guardar y actualizar el código:

CLONE: Al iniciar un nuevo proyecto o unirse a uno, se descarga la copia local del repositorio desde Azure DevOps a VS Code.

CODE (VS Code): Se escribe el código CSS en los archivos correspondientes dentro de las carpetas de arriba.

COMMIT: Se guardan los cambios localmente con un mensaje descriptivo (Source Control / Commit).

PUSH: Se envían los cambios a la nube de Azure DevOps (Push / Sync Changes).

¡Bienvenido a la forma estandarizada de construir proyectos digitales en SBM!