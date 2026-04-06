# Password Strength Analyzer - Android MVP

Este proyecto es una aplicación Android desarrollada en **Java** que permite medir la fortaleza de una contraseña en tiempo real mientras el usuario la escribe. El objetivo principal es demostrar la implementación del patrón de diseño **MVP (Model-View-Presenter)** y el proceso de preparación para la distribución de un aplicativo.

## 🚀 Características

- **Validación en tiempo real:** Análisis instantáneo mediante `TextWatcher`.
- **Lógica de Fortaleza:**
  - 🔴 **Weak:** Menos de 5 caracteres.
  - 🟡 **Medium:** 5 o más caracteres, pero sin mayúsculas.
  - 🟢 **Strong:** 5 o más caracteres y al menos una mayúscula.
- **Arquitectura Limpia:** Separación estricta de responsabilidades usando MVP.

## 🏗️ Arquitectura (MVP)

La aplicación sigue el patrón **Modelo-Vista-Presentador** para asegurar que el código sea testeable y escalable:

- **Model (`PasswordModel.java`):** Contiene las reglas de negocio y la lógica de validación.
- **View (`PasswordView.java` / `MainActivity.java`):** Interfaz que muestra los datos al usuario y detecta eventos de entrada.
- **Presenter (`PasswordPresenter.java`):** Actúa como intermediario, procesando la entrada de la vista y actualizándola según los resultados del modelo.

## 🛠️ Tecnologías y Herramientas

- **Lenguaje:** Java
- **IDE:** Android Studio
- **Control de Versiones:** Git / GitHub
- **Seguridad:** Firma digital mediante JKS (Java KeyStore) para versiones de producción.
- **Distribución:** Preparado para formato Android App Bundle (.aab).

## 📦 Instalación y Uso

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/Lennoxamazing/programacion-en-android/readme.md](https://github.com/Lennoxamazing/programacion-en-android/readme.md)
