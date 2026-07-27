# CoronasDeJusticia.com — Paquete completo para GitHub + Vercel

## Archivos

| Archivo | Qué hace |
|---|---|
| `index.html` | Página principal del ministerio (ES/EN/PT) |
| `test.html` | Caja de Herramientas Ministerial — test completo |
| `logo.jpeg` | Logo del ministerio |
| `vercel.json` | Configuración de rutas para Vercel |
| `package.json` | Metadata del proyecto |

## Cómo subir a GitHub (3 pasos)

1. Ve a **github.com** → botón verde **New** → ponle nombre: `coronas-site`
2. Clic en "uploading an existing file" → arrastra los 5 archivos de esta carpeta
3. Clic en **Commit changes**

## Cómo publicar en Vercel (3 pasos)

1. Ve a **vercel.com** → Add New Project → **Continue with GitHub**
2. Selecciona el repositorio `coronas-site` → clic en **Deploy**
3. En 60 segundos tienes una URL pública (ej. `coronas-site.vercel.app`)

## Cómo conectar CoronasDeJusticia.com

1. En Vercel → Settings → Domains → escribe: `coronasdejusticia.com`
2. Vercel te da 2 registros DNS → los pegas donde compraste el dominio
3. En menos de 24 horas el dominio apunta al sitio

## Cómo actualizar en el futuro

Cuando haya un cambio:
1. Recibe el archivo actualizado de Claude
2. Ve al repositorio en GitHub → clic en el archivo → ícono lápiz
3. Pega el nuevo contenido → **Commit changes**
4. Vercel republica automáticamente en segundos

## URLs del sitio

- `coronasdejusticia.com` → página principal
- `coronasdejusticia.com/test` → Caja de Herramientas Ministerial
- Analizador de Versículos → botón en la página principal (abre ChatGPT)
