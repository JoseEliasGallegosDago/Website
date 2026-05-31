# joseeliasgallegos.com — GitHub Pages

## Archivos de la web

- `index.html` — Página principal (Home)
- `research.html` — Research
- `teaching.html` — Teaching
- `vita.html` — Vita
- `contact.html` — Contact
- `style.css` — Estilos compartidos
- `CNAME` — Dominio personalizado (NO borrar)

## Archivos PDF que debes subir tú

Estos ficheros están enlazados en la web pero no están incluidos aquí.
Debes subirlos manualmente a la raíz del repositorio:

- `cv_bancodeespana.pdf`
- `research_statement.pdf`
- `gallegos.pdf` (Inflation Persistence paper)
- `onlineappendix.pdf`
- `supplementarymaterial.pdf`
- `dt2309.pdf`
- `manuscript.pdf` (HANK beyond FIRE)
- `repository.zip`
- `em.pdf` (Behavioral Hybrid NKM)
- `online_appendix.pdf`
- `replication_em.zip`
- `vol._20_no._7_diciembre-2020.pdf`
- `mac.20200096.pdf`
- `17531.pdf`
- `adgq_wp.pdf`
- `be2204-it-box3.pdf`
- `excellent_teaching_mention.pdf`

## Instrucciones de despliegue en GitHub Pages

### Paso 1: Crear cuenta en GitHub
Ve a https://github.com/signup y crea una cuenta (gratis).

### Paso 2: Crear un repositorio
1. Haz clic en "New repository" (botón verde arriba a la derecha)
2. Ponle el nombre: `joseeliasgallegos.com` (o cualquier nombre)
3. Márcalo como **Public**
4. Haz clic en "Create repository"

### Paso 3: Subir los archivos
1. En la página del repositorio, haz clic en "uploading an existing file"
2. Arrastra TODOS los archivos de esta carpeta (incluido CNAME)
3. Haz clic en "Commit changes"

### Paso 4: Activar GitHub Pages
1. Ve a Settings del repositorio (pestaña de arriba)
2. En el menú izquierdo, haz clic en "Pages"
3. En "Source", selecciona "Deploy from a branch"
4. En "Branch", selecciona "main" y carpeta "/ (root)"
5. Haz clic en "Save"

### Paso 5: Configurar el dominio personalizado
1. En la misma página de Pages, en "Custom domain" escribe: `www.joseeliasgallegos.com`
2. Haz clic en "Save"

### Paso 6: Cambiar los DNS (en el panel de tu registrador de dominio)
Esto depende de dónde tengas el dominio. Necesitas añadir estos registros:

**Registros A (para el apex domain joseeliasgallegos.com):**
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**Registro CNAME (para www):**
```
Nombre: www
Valor: TU_USUARIO.github.io
```
(sustituye TU_USUARIO por tu nombre de usuario de GitHub)

Los cambios DNS pueden tardar hasta 24h en propagarse.

### Paso 7: Activar HTTPS
Una vez que el dominio esté verificado, en la página de Pages
marca la casilla "Enforce HTTPS".

---
¡Listo! Tu web estará en https://www.joseeliasgallegos.com
