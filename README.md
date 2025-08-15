# reportefinal

Proyecto simple con Tailwind CSS local.

Cómo usar

- Instalar dependencias:

```powershell
npm install
```

- Ejecutar Tailwind en modo watch durante desarrollo:

```powershell
npm run dev
```

- Compilar CSS para producción:

```powershell
npm run build
```

- Servir la carpeta (opcional) para ver `index.html`:

```powershell
# si tienes http-server instalado globalmente
npx http-server . -p 8080
```

Notas

- `index.html` ya enlaza `./dist/output.css`.
- Si no ves estilos, asegúrate de correr `npm run dev` y refrescar el navegador sin cache (Ctrl+F5).
