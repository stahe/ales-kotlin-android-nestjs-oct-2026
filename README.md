# Un ejemplo cliente/servidor - Kotlin Android / NestJS (2026)

Este repositorio corresponde al curso **"Un ejemplo cliente/servidor - Kotlin Android / NestJS (2026)"**, publicado en:

**https://stahe.github.io/ales-kotlin-android-nestjs-oct-2026/**

## Descripción general

Este documento adapta la aplicación educativa **RdvMedecins** (agenda de citas médicas), que ya se abordó en cursos sobre Angular, React, Vue.js y Flutter, a una aplicación Android nativa. Aquí se presenta una versión **Android**: un cliente escrito en **Kotlin** con **Jetpack Compose** (Material 3), que se apoya en un servidor **NestJS** (TypeScript) que expone una API JSON protegida mediante autenticación JWT (roles ADMIN / USER).

Este documento ofrece una guía paso a paso que sigue la progresión del curso [Un ejemplo cliente/servidor - Flutter / NestJS (2026)](https://stahe.github.io/ales-flutter-nestjs-sept-2026/), del cual toma el servidor, la base de datos y la arquitectura del cliente: cada concepto de Jetpack Compose se vincula con su equivalente en Flutter. Los fundamentos del lenguaje Kotlin se tratan en el [curso de Kotlin](https://stahe.github.io/ales-kotlin-oct-2026/).

El curso abarca:

- la configuración del entorno de desarrollo (Android Studio, Android SDK, Gradle, creación de un proyecto Compose, emulador y teléfono Android);
- la instalación y ejecución del servidor NestJS de la aplicación (base de datos MySQL, configuración, pruebas con un navegador y con Postman);
- una introducción a Android y Jetpack Compose (actividades, funciones `@Composable`, estado y recomposición, `CompositionLocal`, corrutinas, ciclo de vida y `ViewModel`);
- un recorrido detallado, archivo por archivo, del cliente Kotlin de la aplicación RdvMedecins (OkHttp, kotlinx.serialization, SharedPreferences, Material 3);
- la ejecución de la aplicación en un emulador y en un teléfono, abordando los problemas propios de los dispositivos móviles (dirección del servidor, `adb reverse`, tráfico HTTP sin cifrar, rotación de pantalla, pantallas estrechas), la generación de un APK y una visión general de Kotlin Multiplatform;
- una conclusión sobre lo construido y sugerencias para seguir explorando.

## Autores

- **Autor principal:** IA Claude (Anthropic)
- **Revisor:** [Serge Tahé](https://stahe.github.io)
