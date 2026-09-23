# Multiva Automation QA

Proyecto para la automatización de pruebas para la página de Multiva utilizando [Playwright](https://playwright.dev/).

## Requisitos Previos

- [Node.js](https://nodejs.org/) (versión 18 o superior)
- npm (incluido con Node.js)

## Instalación

1. Clonar el repositorio:
   ```bash
   git clone <url-del-repositorio>
   cd multiva-automation-qa
   ```

2. Instalar las dependencias:
   ```bash
   npm install
   ```

3. Instalar los navegadores de Playwright:
   ```bash
   npx playwright install
   ```

## Comandos Principales

A continuación se detallan los comandos más utilizados para ejecutar las pruebas:

- **Ejecutar todas las pruebas:**
  ```bash
  npx playwright test
  ```

- **Ejecutar pruebas con navegador visible (Headed):**
  ```bash
  npx playwright test --headed
  ```

- **Ejecutar un archivo de prueba específico:**
  ```bash
  npx playwright test tests/login.spec.ts
  ```

- **Abrir el Modo UI interactivo:**
  ```bash
  npx playwright test --ui
  ```

- **Mostrar el último reporte generado:**
  ```bash
  npx playwright show-report
  ```

## Estructura del Proyecto

- `tests/`: Contiene los archivos de prueba (.spec.ts).
- `playwright.config.ts`: Configuración global de Playwright.
