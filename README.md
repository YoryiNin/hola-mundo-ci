# Hola Mundo - Integración Continua

Este repositorio es una práctica de Integración Continua (CI) utilizando GitHub Actions.

##  Objetivo
Implementar un flujo de Integración Continua que ejecute un programa Hola Mundo y envíe una notificación automática al realizar un push a la rama main.

## 🛠 Tecnologías usadas
- JavaScript (Node.js)
- GitHub Actions
- ntfy.sh
- Git

## ⚙ Funcionamiento
Cada vez que se realiza un push a la rama `main`, GitHub Actions:
1. Descarga el repositorio
2. Ejecuta el programa Hola Mundo
3. Envía una notificación al canal `devops-itla` en ntfy.sh

##  Resultado
Se recibe una alerta en tiempo real confirmando que el código fue subido correctamente.

## Autor
YoryiNin
