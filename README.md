# 🌐 Colaboradores Web

Este repositorio forma parte del curso **Fundamentos de Git y GitHub para profesores**.  
Cada participante contribuye creando su **propia tarjeta HTML** dentro de una página web colaborativa, utilizando herramientas fundamentales como **Git**, **ramas** y **Pull Requests**.

El resultado final se publica con **GitHub Pages**, mostrando de forma visual las contribuciones del grupo.

---

## 🎨 ¿Qué hace especial este proyecto?

Cada colaborador puede **personalizar su tarjeta y su estilo** como desee.  
Aquí no hay un diseño único: cada fork puede modificar el `style.css` para reflejar su identidad o creatividad.

---

## 🧭 Estructura del repositorio

```

.
├── colaboradores/
│   ├── benji-rodriguez.html      ← Ejemplo de tarjeta personalizada
│   └── plantilla.html            ← Archivo base para comenzar
├── index.html                    ← Página principal (muestra todas las tarjetas)
├── LICENSE
├── README.md
└── style.css                     ← Puedes modificarlo a tu gusto

```

---

## ✅ ¿Cómo colaborar?

### 1. Haz fork del repositorio

Desde GitHub, haz clic en el botón `Fork` en la parte superior derecha.

---

### 2. Clona tu fork localmente

```bash
git clone https://github.com/tu-usuario/colaboradores-web.git
cd colaboradores-web
```

---

### 3. Crea tu tarjeta personalizada

- Copia la plantilla:

  ```bash
  cp colaboradores/plantilla.html colaboradores/tu-nombre.html
  ```

- Edita `colaboradores/tu-nombre.html` con tus datos (nombre, lenguaje favorito, GitHub, etc.).
- Puedes modificar `style.css` para personalizar el estilo de tu fork.

---

### 4. Agrega tu tarjeta al `index.html`

Abre el archivo `index.html` y **pega el contenido HTML** de tu tarjeta justo donde se indica:

```html
<!-- colaboradores/tu-nombre.html -->
<div class="card">
  <h2>Tu Nombre</h2>
  <p><strong>Lenguaje favorito:</strong> Python</p>
  <p><a href="https://github.com/tu-usuario">GitHub</a></p>
</div>
```

> 🧠 **Nota**: No uses `iframe`. Copia el contenido de tu tarjeta directamente.

---

### 5. Crea una rama con tu nombre de usuario

Es una buena práctica que la rama que uses para tu aporte lleve tu nombre de usuario:

```bash
git checkout -b tu-usuario-tarjeta
```

---

### 6. Guarda y sube tus cambios

```bash
git add .
git commit -m "Agrego mi tarjeta de colaborador"
git push origin tu-usuario-tarjeta
```

---

### 7. Crea un Pull Request

- Ve a tu fork en GitHub.
- Crea un Pull Request desde tu rama hacia la rama `main` del repositorio original.

---

## 🌍 Publicación con GitHub Pages

Puedes publicar tu fork con GitHub Pages:

1. Ve a la configuración (`Settings`) de tu fork.
2. Busca la sección **Pages**.
3. Elige la rama `main` y elige `/ (root)` como carpeta.
4. Guarda los cambios.

Tu página estará disponible en:
`https://tu-usuario.github.io/colaboradores-web`

---

## 🔄 Mantén tu fork actualizado

Cuando otros colaboradores hagan aportes, puedes actualizar tu fork con los cambios del repositorio base:

```bash
git remote add upstream https://github.com/usuario-original/colaboradores-web.git
git pull upstream main
```

---

## ⚠️ Nota importante

Este archivo `README.md` **debe conservarse** con instrucciones claras sobre cómo colaborar.
Si deseas mejorarlo, puedes hacer un Pull Request.

---

¡Esperamos ver tu aporte y estilo personal en este proyecto! 🎉

```

```
