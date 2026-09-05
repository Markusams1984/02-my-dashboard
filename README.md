# My Dashboard

Dashboard construido como parte de un curso de Next.js.

## Tecnologías

- **Next.js 16** (App Router)
- **React 19**
- **TypeScript 5**
- **Tailwind CSS 4**
- **react-icons**

## Instalación y uso

```bash
npm install
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) en el navegador.

Otros scripts: `npm run build`, `npm start`, `npm run lint`.

## Características

- **Shopping cart**: `CartCounter` es un client component que maneja el conteo con `useState` y recibe su valor inicial por props.
- **Sidebar**: menú definido como arreglo de rutas, renderizado con `Link` y marcando la ruta activa con `usePathname`.

## Estructura

```
app/
├── components/     # Sidebar y SidebarMenuItem
├── dashboard/      # Sección del dashboard
│   ├── counter/    # Página del contador
│   ├── main/       # Página principal
│   └── layout.tsx  # Layout con sidebar
├── shopping-cart/  # CartCounter (client component)
├── globals.css     # Estilos globales (Tailwind)
├── layout.tsx      # Layout raíz
└── page.tsx        # Home
public/             # Recursos estáticos
```
