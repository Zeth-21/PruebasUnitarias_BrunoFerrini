# 🧪 Pruebas Unitarias y Calidad de Código - Bruno Ferrini

Este repositorio contiene la implementación de un flujo de **Integración Continua (CI)** diseñado para automatizar las pruebas unitarias y asegurar la calidad del código mediante métricas estrictas.

## 🚀 Características del Pipeline

El proyecto utiliza **GitHub Actions** para ejecutar automáticamente dos validaciones principales en cada `push` a la rama `main`:

* **Tests y Cobertura (Jest):** Ejecuta la suite de pruebas unitarias y verifica que el código mantenga un umbral de cobertura mínimo del **70%**. Si no se alcanza, el pipeline se bloquea.
* **Análisis Estático (SonarCloud):** Inspecciona el código fuente en busca de vulnerabilidades de seguridad, *bugs*, código duplicado y *code smells*, aplicando un *Quality Gate* profesional.

## 🛠️ Tecnologías Utilizadas

* **Entorno:** Node.js 20
* **Testing:** Jest
* **CI/CD:** GitHub Actions
* **Análisis de Calidad:** SonarCloud

## 📄 Documentación

Para ver el informe detallado de este laboratorio, la configuración de los *secrets* y las evidencias de ejecución, revisa el siguiente documento:

👉 [Ver Documentación Completa del Proyecto](https://drive.google.com/file/d/1joXdL9LhnSB3K99C2LCBqt_Konp-jePK/view?usp=sharing)

---
*Desarrollado como parte de las prácticas de aseguramiento de calidad de software.*
