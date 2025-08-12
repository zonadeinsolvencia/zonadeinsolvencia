# Zona de Insolvencia — Landing (Next.js 14 + Tailwind)

## Cómo publicar (sin programar)
1. Crea cuenta en Vercel: https://vercel.com/signup
2. Crea una cuenta en GitHub (si no tienes): https://github.com/signup
3. En GitHub, crea un repositorio vacío llamado `zona-de-insolvencia-landing` y sube todos los archivos de esta carpeta (puedes arrastrar y soltar desde el navegador).
4. En Vercel, haz clic en **Add New > Project > Import Git Repository** y elige ese repositorio.
5. Vercel detectará **Next.js** y con **Deploy** te dará una URL pública.

## Editar textos
- Abre `app/page.tsx` y modifica títulos, textos o secciones.
- Las páginas legales están en `app/(legal)/*`.

## Analytics (opcional)
- En Vercel > Project Settings > Environment Variables, agrega:
  - `NEXT_PUBLIC_GA_ID` (por ejemplo `G-XXXXXXXXXX`)
  - `NEXT_PUBLIC_META_PIXEL_ID` (por ejemplo `1234567890`)
- Vercel redeploy y listo.

## Scripts
- `npm run dev` para desarrollo local
- `npm run build && npm start` para producción
