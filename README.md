# 🎂 HappyBirthday App - Android

[![Kotlin Version](https://img.shields.io/badge/Kotlin-1.9.0-blue.svg)](https://kotlinlang.org)
[![Compose Version](https://img.shields.io/badge/Jetpack%20Compose-1.5.0-orange.svg)](https://developer.android.com/jetpack/compose)

Una aplicación Android que muestra una tarjeta de cumpleaños animada con Jetpack Compose, perfecta para enviar felicitaciones digitales.

<p align="center">
  <img src="https://github.com/rodrigoangeloni/ipdm-oto-2025-rodrigo_angeloni_ejercicios-1-2/raw/main/app/src/main/res/drawable-nodpi/screenshot.png" width="300" alt="Captura de HappyBirthday">
</p>

## ✨ Características

- Interfaz moderna con Jetpack Compose
- Diseño responsive para todos los dispositivos
- Efectos visuales con transparencia (`alpha = 0.5F`)
- Previsualización en tiempo real con `@Preview`
- Fácil personalización de textos e imágenes

## 🛠 Tecnologías

- **Lenguaje**: Kotlin 100%
- **UI**: Jetpack Compose + Material Design 3
- **Arquitectura**: ComponentActivity + Composable
- **Compatibilidad**: Android 8.0+ (API 26)

## 🏗 Estructura del proyecto

```bash
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/happybirthday/
│   │   │   └── MainActivity.kt       # Lógica principal
│   │   └── res/
│   │       ├── drawable-nodpi/       # Recursos de imagen
│   │       │   └── screenshot.png   # Captura de la app
│   │       ├── drawable/            # Assets gráficos
│   │       └── values/
│   │           └── strings.xml      # Textos traducibles
