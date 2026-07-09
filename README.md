# 📄 CV Web con React

## 📌 Descripción

Este proyecto consiste en una hoja de vida (Currículum Vitae) desarrollada como una aplicación web utilizando **React**, **HTML** y **CSS**. La información del CV se encuentra organizada mediante componentes reutilizables, lo que facilita su mantenimiento y futuras actualizaciones.

El diseño es responsive, permitiendo que el CV se adapte correctamente a computadoras, tablets y dispositivos móviles. Además, incorpora una opción para descargar el currículum en formato PDF mediante la función de impresión del navegador.

---

## 🚀 Características

- Diseño limpio y profesional.
- Adaptable a dispositivos móviles (Responsive Design).
- Información organizada mediante componentes de React.
- Sección de datos personales.
- Sección de experiencia profesional.
- Sección de formación académica.
- Habilidades informáticas.
- Idiomas.
- Fotografía de perfil.
- Botón para descargar el CV en PDF.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- React 18
- ReactDOM
- Babel Standalone
- JavaScript (ES6)

---

## 📂 Estructura del proyecto

```
CV-Web/
│
├── index.html
├── foto.jpg
└── README.md
```

---

## ⚙️ Instalación

No es necesario instalar dependencias ni utilizar Node.js.

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
```

2. Entrar a la carpeta del proyecto:

```bash
cd tu-repositorio
```

3. Abrir el archivo **index.html** en cualquier navegador.

También puedes utilizar la extensión **Live Server** de Visual Studio Code para una mejor experiencia.

---

## 📱 Compatibilidad

El proyecto funciona correctamente en:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Opera
- Safari

También puede visualizarse desde teléfonos móviles y tablets.

---

## 📄 Descargar el CV

El botón **"Descargar como PDF"** utiliza la función:

```javascript
window.print();
```

Esta permite guardar el currículum en formato PDF desde el navegador.

---

## 📸 Personalización

Puedes modificar fácilmente la información editando el objeto:

```javascript
const datosCV = {
    ...
}
```

Desde allí puedes cambiar:

- Nombre
- Cargo profesional
- Correo electrónico
- Teléfono
- LinkedIn
- Datos personales
- Experiencia laboral
- Formación académica
- Habilidades
- Idiomas
- Certificados

Para cambiar la fotografía solo reemplaza el archivo:

```
foto.jpg
```

por una imagen con el mismo nombre.

---

## 📚 Componentes implementados

El proyecto está dividido en los siguientes componentes de React:

- Encabezado
- Sidebar
- Experiencia
- Formación
- Certificados
- App

Cada componente tiene una función específica para mantener el código organizado y reutilizable.

---

## 👨‍💻 Autor

**Cristhian Joel Silva Martínez**

Estudiante de Tecnología Superior en Desarrollo de Software.

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos y de aprendizaje.
