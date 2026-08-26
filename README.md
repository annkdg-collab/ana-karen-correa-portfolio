# Ana Karen Correa — Portfolio

Repositorio preparado para migrar el portfolio actual de AppDeploy.

## Estado de la migración

- Fuente revisada: AppDeploy `ana-karen-correa-portfolio-ekngt8`
- Stack detectado: React 19 + Vite + TypeScript + Tailwind CSS
- Backend detectado: AppDeploy SDK + almacenamiento persistente para imágenes de proyectos
- Hero actual: conserva `DISEÑO.`, `TECNOLOGÍA.` y `CALIDAD. IA.`
- LinkedIn actual detectado: `https://www.linkedin.com/in/ana-karen-correa-acuna-60368aa6/`
- El repositorio estaba vacío al iniciar la migración.

## Archivos fuente detectados

- `src/App.tsx`
- `src/index.css`
- `src/main.tsx`
- `src/senior.css`
- `backend/index.ts`
- `index.html`
- `package.json`
- `tailwind.config.js`
- `postcss.config.js`
- `tsconfig.json`
- `vite.config.ts`
- `tests/tests.txt`

## Assets pendientes de migrar

El snapshot de AppDeploy revisado no incluye los binarios de `public/resources/`, aunque el código actual referencia recursos como:

- `public/resources/Ana-Karen-Correa-Acuna-CV.pdf`
- `public/resources/AKOS-cover.jpg`
- `public/resources/AKOS-gallery-01.jpg`
- `public/resources/AKOS-gallery-02.jpg`
- `public/resources/AKOS-gallery-03.jpg`
- `public/resources/Gym-cover.jpg`
- `public/resources/Leonas-UAT.jpg`

No se han inventado ni reemplazado estos archivos. Deben incorporarse desde los archivos originales antes de considerar la migración como completa.

## Regla de migración

Preservar el portfolio existente. No rediseñar el Hero ni eliminar contenido, proyectos, botones o textos existentes. La corrección funcional debe mantener la estructura visual actual y centrarse en persistencia de archivos, CV y la integración visual de AKLEX.
