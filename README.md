# 📊 Sistema Contable Web — Registro y Control de Partida Doble

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Live_Demo-GitHub_Pages-222222?style=for-the-badge&logo=github)](https://aleumg.github.io/sistema-contable-web/)

Aplicación web completa e interactiva para el **registro contable formal bajo el principio de partida doble**, administración de catálogo de cuentas, elaboración de balances y exportación de reportes. Diseñada combinando formación formal de **Perito Contador** con técnicas modernas de ingeniería de software web.

🔗 **[Probar Demo en Vivo](https://aleumg.github.io/sistema-contable-web/)**

---

## 🌟 Funcionalidades del Sistema

### 1. 💼 Balance de Saldos Inicial
* Configuración de la entidad económica, fecha de inicio y periodo contable.
* Carga dinámica de cuentas de Activo, Pasivo y Patrimonio con clasificación por naturaleza contable (Debe / Haber).
* Cálculo reactivo de totales y verificación automática de diferencia cero ($\text{Debe} - \text{Haber} = 0$) antes de aperturar el ejercicio contable.

### 2. 📖 Libro Diario (Asientos y Partidas Contables)
* Generación de partidas contables con fecha, número correlativo de partida, concepto/descripción y cuentas intervinientes.
* Validación estricta de cuadre: no permite asentar partidas desbalanceadas.
* Historial tabular cronológico de todas las partidas registradas.

### 3. 📑 Libro Mayor & T-Gráficas
* Centralización automática y cálculo de movimientos acumulados por cuenta.
* Determinación instantánea del saldo deudor o saldo acreedor según el flujo de transacciones.

### 4. ⚖️ Balance de Comprobación y Saldos
* Consolidación final del ejercicio con sumas del Debe y Haber y balance de saldos.
* Resumen visual de estado de cuadre contable.

### 5. 📥 Exportación y Persistencia
* Integración con exportación de datos y formatos compatibles con hojas de cálculo (Excel).
* Almacenamiento local mediante `LocalStorage` para preservar la sesión de trabajo.

---

## 📁 Estructura del Proyecto

```text
├── index.html          # Estructura de la aplicación, formularios y vistas tabulares
├── UMG.png             # Logotipo institucional de la Universidad Mariano Gálvez
├── logo excel.png      # Icono para exportación de reportes
└── README.md           # Ficha técnica y documentación del sistema
```

---

## 🚀 Ejecución y Uso Local

La aplicación es 100% autónoma y se ejecuta directamente en cualquier navegador moderno:

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/AleUmg/sistema-contable-web.git
   cd sistema-contable-web
   ```
2. **Abrir la aplicación**:
   * Haz doble clic sobre `index.html` para iniciar el sistema contable de inmediato.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5**: Estructura semántica, formularios accesibles y tablas dinámicas.
* **CSS3**: Variables CSS nativas, diseño responsivo y tipografía moderna (`Segoe UI`).
* **JavaScript (Vanilla ES6+)**: Manipulación del DOM, validación estricta de partida doble y algoritmos contables.

---

## 👨‍💻 Autor

* **Alejandro Ajpu Baten Rojas** — [GitHub: @AleUmg](https://github.com/AleUmg)
* **Perito Contador** & Estudiante de **Ingeniería en Sistemas de Información** — Universidad Mariano Gálvez de Guatemala (UMG).
