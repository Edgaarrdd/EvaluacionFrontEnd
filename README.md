# Proyecto de FrontEnd 1

## 📌 Instrucciones Generales

Cada alumno deberá diseñar e implementar un sitio web cumpliendo los requisitos mínimos descritos en la sección **Requerimientos**. 

El estudiante debe escoger uno de los 5 casos entregados por el docente, o proponer uno propio. Los casos están relacionados con empresas que necesitan promocionarse en internet.

> **Importante**:  
> Esta es la primera evaluación de la asignatura.  
> ✅ **Fecha de entrega**: 18.06.2025  
> 🔁 **Feedback disponible**: 11.06.2025  
> ❌ **Entregas fuera de plazo** tendrán nota máxima 3,9  
> ⛔ **No entregar** el 18.06.2025 implica nota mínima (1,0 según normativa INACAP)

---

## ✅ Requerimientos

Para optar a la **nota máxima**, se deben cumplir los siguientes puntos:

- [ ] Crear un **sitio web** para una empresa.
- [ ] Crear un **logotipo**.
- [ ] Crear un **nombre de empresa** (o usar el proporcionado).
- [ ] Tener **al menos 4 páginas navegables**.
- [ ] Usar el framework **Bootstrap 4.5** (obligatorio).
- [ ] Sitio debe ser **responsive** (visualización óptima al menos en Smartphone).
- [ ] Código **semántico** y respetuoso con nombres de archivos/carpetas.
- [ ] Incluir **logo** y **colores corporativos**.
- [ ] Incluir un **favicon**.
- [ ] Usar **imágenes** relacionadas a la empresa (puede usar IA).
- [ ] Proyecto debe estar **publicado en GitHub** con al menos **3 commits** (uno por cada página desarrollada idealmente).

---

## 🧩 Secciones a Implementar

### 1. `Index.html`
- NavBar (barra de navegación)
- Carrusel o slider
- Sección de contenido principal
- Footer (pie de página)

### 2. `SobreNosotros.html`
- NavBar
- Información de la compañía: equipo, historia, misión, visión
- Footer

### 3. `Servicios.html`
- NavBar
- 6 productos o servicios con:
  - Imagen
  - Descripción
  - Precio
  - Condiciones
- Footer

### 4. `Contacto.html`
- NavBar
- Formulario de contacto
- Mapa de ubicación de la empresa
- Footer

---

## 📦 Caso Elegido

### 🛵 **CASO 4: Empresa de Reparto Urbano – “FastGo”**

#### Contexto:
FastGo realiza **entregas express** dentro de la ciudad.  
Actualmente cuentan con una **app de tracking**, pero carecen de visibilidad general sobre:
- Rendimiento por zona
- Rendimiento por repartidor
- Rendimiento por cliente


# Proyecto de FrontEnd 2 – Evaluación II

## 🎯 Objetivo General

Consolidar el manejo de formularios en HTML utilizando **Bootstrap**, aplicar **validaciones robustas** e implementar el almacenamiento de datos en **LocalStorage**. El objetivo es validar los datos del formulario (incluyendo el correo electrónico), almacenarlos y permitir su gestión completa (listar, editar y eliminar).

---

## ✅ Requerimientos

- [ ] Utilizar el mismo caso de la Evaluación I o crear una nueva **interfaz web con formulario de contacto**.
- [ ] Implementar el formulario con **Bootstrap**.
- [ ] Validar el **formato del correo electrónico**.
- [ ] Guardar los datos del formulario en **LocalStorage** luego de una validación exitosa.
- [ ] Mostrar una **lista de todos los registros** almacenados en LocalStorage.
- [ ] Permitir la **edición** de registros existentes y actualizarlos en LocalStorage.
- [ ] Permitir la **eliminación** de registros individuales.
- [ ] Utilizar la **librería jQuery** para todas las funcionalidades.
- [ ] Integrar la API de países:  
  `https://restcountries.com/v3.1/lang/spanish`.

---

## 🧩 Campos del Formulario

El formulario de contacto debe incluir los siguientes campos:

- [ ] **Nombre**
- [ ] **Teléfono**
- [ ] **Email** (con validación de formato)
- [ ] **País** (cargado desde la API)
- [ ] **Nombre Oficial del País**  
  (desde `name.official` o preferiblemente `name.nativeName.spa.official`)
- [ ] **Comentarios**

---

## 🌐 Integración con API REST

Usar la API `https://restcountries.com/v3.1/lang/spanish` para:

- Obtener la **lista de países** en idioma español.
- Cargar dinámicamente los campos **País** y **Nombre Oficial del País** en el formulario.

---

## 💻 Control de Versiones y Entrega

- [ ] Publicar el proyecto en **GitHub** con mínimo 3 commits significativos.
- [ ] Alternativamente, enviar el proyecto por **correo electrónico** si así se indica por el docente.
- [ ] Asegúrate de incluir en el repositorio el archivo `README.md` con toda la información del proyecto.


