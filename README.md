# dcc-suite-enterprise
All-in-one workspace for airline customer service agents. Built with vanilla JavaScript &amp; CSS, this platform optimizes call handling, technical notes
🛡️ DCC Suite | Enterprise Edition

**DCC Suite** es una plataforma integral de productividad de alto rendimiento diseñada para centralizar y optimizar el flujo de trabajo de los agentes de atención a clientes. Desarrollada bajo una arquitectura **Zero-Trust Client-Side**, garantiza que todos los datos sensibles se procesen localmente en la memoria y se destruyan al cerrar la sesión, sin transmitir absolutamente nada a servidores externos.

## ✨ Características Principales
*   **🖥️ Extracción OCR Local:** Captura y procesa datos de sistemas heredados de forma 100% local.
*   **🚨 Gestor de Escalamientos Dinámico:** Generación automática de textos con mapas de aviones interactivos (Airbus A320 y A321) para la asignación de asientos en tiempo real.
*   **📊 Calculadora ROP Inteligente:** Cálculo dinámico de vouchers y división equitativa del monto por pasajero.
*   **📱 Directorio Integrado:** Búsqueda rápida de extensiones y departamentos con copiado rápido.
*   **📓 Bitácora Enmascarada:** Registro seguro de llamadas con protección automática de datos personales (PII).
*   **🌗 Interfaz Adaptable:** Modo oscuro inteligente con ajuste de contraste para reducir la fatiga visual en turnos largos.

## 🔒 Arquitectura de Seguridad
*   **Zero Data Leak:** Procesamiento local en `SessionStorage`. Nada viaja por la red.
*   **Anti-Inspection Protocols:** Bloqueo de herramientas de desarrollador (F12 / Clic derecho) para proteger la lógica del negocio.
*   **Obfuscated Logic Layer:** Capa de ofuscación de código (Base64 + JS) para resistir la ingeniería inversa y el escaneo por IA.
