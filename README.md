# Mother's Day Letter

![Mother's Day Letter](https://github.com/user-attachments/assets/2af379a8-b1eb-4133-86d7-50f8cd57f941)

Una aplicación móvil desarrollada en Unity 6.1 con integración de **Vuforia Engine**, diseñada para ofrecer una experiencia interactiva de realidad aumentada (AR) en conmemoración del Día de las Madres. Compatible con dispositivos Android que ejecuten **Android 6.0 (Marshmallow)** o superior.

---

## 📑 Tabla de Contenido

- [📌 Introducción](#introducción)
- [✨ Características Principales](#características-principales)
- [🛠️ Requisitos del Sistema](#requisitos-del-sistema)
- [🧰 Tecnologías Utilizadas](#tecnologías-utilizadas)
- [⚙️ Instrucciones de Compilación](#instrucciones-de-compilación)
- [📲 Instalación en Dispositivos Android](#instalación-en-dispositivos-android)
- [🧪 Consideraciones de Desarrollo](#consideraciones-de-desarrollo)
- [🙏 Créditos o Agradecimientos](#créditos-o-agradecimientos)
- [📄 Licencia](#licencia)

---

## 📌 Introducción

Esta aplicación de realidad aumentada fue creada para brindar una experiencia visual y emocional especial durante el Día de las Madres. Al escanear una imagen o marcador específico, los usuarios pueden visualizar contenido 3D, mensajes personalizados, animaciones y más.

El objetivo es proporcionar una experiencia tecnológica accesible que combine afecto, creatividad e innovación.

---

## ✨ Características Principales

- Reconocimiento de imágenes mediante **Vuforia Engine**.
- Visualización de modelos 3D animados.
- Efectos visuales y sonido envolvente.
- Interfaz intuitiva y optimizada para dispositivos móviles.
- Configuración personalizable para diferentes tipos de contenido.

---

## 🛠️ Requisitos del Sistema

| Componente             | Requisito mínimo                        |
|------------------------|------------------------------------------|
| **Sistema Operativo**  | Android 6.0 (Marshmallow) o superior     |
| **RAM**                | 2 GB                                     |
| **CPU**                | ARMv7-A (32-bit) o ARM64 (64-bit)        |
| **Resolución**         | 720x1280 o superior                      |
| **Permisos**           | Cámara, Almacenamiento                   |

---

## 🧰 Tecnologías Utilizadas

- **[Unity 6.1](https://unity.com/releases)** – Motor de desarrollo multiplataforma.
- **[Vuforia Engine](https://developer.vuforia.com/)** – SDK de realidad aumentada.
- **C#** – Lenguaje de programación principal para scripts y lógica.
- **Gradle** – Herramienta de compilación para Android.

---

## ⚙️ Instrucciones de Compilación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Jyhsus/Mother-s-Day-Letter.git

2. Abre el proyecto en Unity 6.1 o superior.

3. Verifica que tengas el módulo de Android instalado en Unity Hub.

4. Importa el paquete de Vuforia Engine desde el Unity Package Manager o desde el portal oficial de Vuforia.

5. Asegúrate de tener una licencia válida de Vuforia (puede ser una licencia de desarrollo gratuita).

6. En Build Settings, selecciona la plataforma Android y configura los siguientes parámetros:

  * Minimum API Level: Android 6.0 (API 23)

  * Graphics API: OpenGLES3 (opcional)

  * Arquitectura: ARMv7 y ARM64

7. Compila el proyecto utilizando Build o Build And Run.

---

## 📲 Instalación en Dispositivos Android

Una vez generado el archivo .apk:

1. Transfiere el archivo al dispositivo Android.

2. Habilita la instalación de aplicaciones desde fuentes desconocidas.

3. Instala el archivo APK y otorga permisos de cámara y almacenamiento al iniciar.

4. Escanea el marcador o imagen objetivo para iniciar la experiencia AR.

---

## 🧪 Consideraciones de Desarrollo

* Entorno de pruebas: Se recomienda probar en dispositivos físicos con cámara funcional. Los emuladores no son compatibles con AR.

* Marcadores: Asegúrate de usar imágenes con alto contraste y complejidad visual para mejorar el reconocimiento.

* Licencia Vuforia: Las aplicaciones publicadas requieren una licencia adecuada para eliminar la marca de agua.

* Optimización: Reduce el tamaño de los modelos y texturas para mejorar el rendimiento en dispositivos de gama media o baja.

---

## 🙏 Créditos o Agradecimientos

Este proyecto fue posible gracias al esfuerzo del equipo de desarrollo, los recursos de la comunidad Unity y el soporte de Vuforia. También agradecemos a todas las madres por su amor y dedicación, fuente de inspiración para esta aplicación.

---

## 📄 Licencia

Este proyecto está licenciado bajo la MIT License. Puedes utilizar, modificar y distribuir este software conforme a los términos establecidos.
