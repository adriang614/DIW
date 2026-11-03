# 🛠️ Entorno de Desarrollo — Rama `develop`

Esta es la **rama de integración predeterminada** del repositorio de **Diseño de Interfaces Web (DIW - 2º DAW)**. 

En esta rama se consolidan, prueban y revisan todos los avances, entregables y baterías de ejercicios procedentes de las ramas específicas de trabajo antes de su publicación definitiva en la rama `main`.

---

## ⚙️ Flujo de Integración

1. **Ramas específicas:** Cada práctica o batería de ejercicios se trabaja en su propia rama aislada (ej. `practica1`, `ejercicios-flexbox`).
2. **Revisión e Integración:** Tras completar una tarea, la rama correspondiente se fusiona (*merge*) en `develop`.
3. **Entrega Final:** Una vez verificada la estabilidad del código en `develop`, se realiza el *merge* hacia `main`.

---

## 📋 Estado actual del desarrollo

* **Prácticas integradas:** Se listan a continuación las entregas que ya han sido fusionadas en esta rama.
* **Próximas incorporaciones:** Contenido en fase de revisión procedente de ramas específicas.

---

## 🚀 Comandos de trabajo habituales

```bash
# Cambiarse a la rama develop y actualizar cambios
git checkout develop
git pull origin develop

# Fusionar una rama específica terminada (ejemplo: practica1)
git merge practica1

# Subir cambios consolidados
git push origin develop# DIW
