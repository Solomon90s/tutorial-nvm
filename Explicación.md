# Guía de Instalación de Node.js con NVM (Windows)

> ⚠️ **MUY IMPORTANTE:** Antes de instalar la gestión de versiones, asegúrate de **no tener Node.js instalado** previamente en el equipo.

## 1. Instalación de NVM
1. Descarga y descomprime el archivo `nvm-setup.zip`.
2. Ejecuta el archivo `.exe` para instalar NVM.

## 2. Uso de NVM desde la Terminal o PowerShell (como administrador)
### Comandos básicos:
- `nvm`
  Muestra una lista de los comandos disponibles.

- `nvm install 22.12.0`
  Instala la versión específica de Node.js (en este caso, la 22.12.0).

- `nvm list`
  Muestra las versiones de Node.js instaladas en el equipo.

- `nvm use 22.12.0`
  Indica que se desea utilizar la versión que acabas de instalar.

- `node -v` o `node version`
  Verifica qué versión de Node.js está activa.

## 3. Instalación de Angular y TypeScript
- `npm i -g @angular/cli`
  Instala globalmente la última versión de Angular CLI.

- `npm i -g typescript`
  Instala globalmente TypeScript.
